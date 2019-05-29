---
title: Module securityhub
aliases:
    - "/reference/pkg/nodejs/@pulumi/aws/securityhub/"
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../">@pulumi/aws</a> &gt; securityhub

<div class="toggleVisible">
<div class="collapsed">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents">
<ul>
<li><a href="#Account">class Account</a></li>
<li><a href="#ProductSubscription">class ProductSubscription</a></li>
<li><a href="#StandardsSubscription">class StandardsSubscription</a></li>
<li><a href="#AccountArgs">interface AccountArgs</a></li>
<li><a href="#AccountState">interface AccountState</a></li>
<li><a href="#ProductSubscriptionArgs">interface ProductSubscriptionArgs</a></li>
<li><a href="#ProductSubscriptionState">interface ProductSubscriptionState</a></li>
<li><a href="#StandardsSubscriptionArgs">interface StandardsSubscriptionArgs</a></li>
<li><a href="#StandardsSubscriptionState">interface StandardsSubscriptionState</a></li>
</ul>

<a href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/account.ts">securityhub/account.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/productSubscription.ts">securityhub/productSubscription.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/standardsSubscription.ts">securityhub/standardsSubscription.ts</a> 
</div>
</div>
</div>


<h2 class="pdoc-module-header" id="Account">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/account.ts#L23">class <b>Account</b></a>
</h2>
<div class="pdoc-module-contents">
<pre class="highlight"><span class='kd'>extends</span> <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

Enables Security Hub for this AWS account.

> **NOTE:** Destroying this resource will disable Security Hub for this AWS account.

> **NOTE:** This AWS service is in Preview and may change before General Availability release. Backwards compatibility is not guaranteed between Terraform AWS Provider releases.

## Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as aws from "@pulumi/aws";

const example = new aws.securityhub.Account("example", {});
```

<h3 class="pdoc-member-header" id="Account-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/account.ts#L34"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> Account(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args?: <a href='#AccountArgs'>AccountArgs</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a Account resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Account-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/account.ts#L32">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#AccountState'>AccountState</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Account'>Account</a></pre>


Get an existing Account resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Account-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L14">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Account-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L107">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Account-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L102">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</pre>
{{% md %}}

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="Account-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L12">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>urn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</pre>
{{% md %}}

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="ProductSubscription">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/productSubscription.ts#L25">class <b>ProductSubscription</b></a>
</h2>
<div class="pdoc-module-contents">
<pre class="highlight"><span class='kd'>extends</span> <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

Subscribes to a Security Hub product.

> **NOTE:** This AWS service is in Preview and may change before General Availability release. Backwards compatibility is not guaranteed between Terraform AWS Provider releases.

## Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as aws from "@pulumi/aws";

const exampleAccount = new aws.securityhub.Account("example", {});
const current = pulumi.output(aws.getRegion({}));
const exampleProductSubscription = new aws.securityhub.ProductSubscription("example", {
    productArn: pulumi.interpolate`arn:aws:securityhub:${current.name}:733251395267:product/alertlogic/althreatmanagement`,
}, {dependsOn: [exampleAccount]});
```

<h3 class="pdoc-member-header" id="ProductSubscription-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/productSubscription.ts#L45"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> ProductSubscription(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#ProductSubscriptionArgs'>ProductSubscriptionArgs</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a ProductSubscription resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ProductSubscription-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/productSubscription.ts#L34">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#ProductSubscriptionState'>ProductSubscriptionState</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#ProductSubscription'>ProductSubscription</a></pre>


Get an existing ProductSubscription resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ProductSubscription-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L14">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ProductSubscription-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L107">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ProductSubscription-arn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/productSubscription.ts#L41">property <b>arn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>arn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The ARN of a resource that represents your subscription to the product that generates the findings that you want to import into Security Hub.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ProductSubscription-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L102">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</pre>
{{% md %}}

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ProductSubscription-productArn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/productSubscription.ts#L45">property <b>productArn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>productArn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The ARN of the product that generates findings that you want to import into Security Hub - see below.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ProductSubscription-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L12">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>urn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</pre>
{{% md %}}

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="StandardsSubscription">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/standardsSubscription.ts#L24">class <b>StandardsSubscription</b></a>
</h2>
<div class="pdoc-module-contents">
<pre class="highlight"><span class='kd'>extends</span> <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

Subscribes to a Security Hub standard.

> **NOTE:** This AWS service is in Preview and may change before General Availability release. Backwards compatibility is not guaranteed between Terraform AWS Provider releases.

## Example Usage

```typescript
import * as pulumi from "@pulumi/pulumi";
import * as aws from "@pulumi/aws";

const exampleAccount = new aws.securityhub.Account("example", {});
const exampleStandardsSubscription = new aws.securityhub.StandardsSubscription("example", {
    standardsArn: "arn:aws:securityhub:::ruleset/cis-aws-foundations-benchmark/v/1.2.0",
}, {dependsOn: [exampleAccount]});
```

<h3 class="pdoc-member-header" id="StandardsSubscription-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/standardsSubscription.ts#L40"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> StandardsSubscription(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#StandardsSubscriptionArgs'>StandardsSubscriptionArgs</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a StandardsSubscription resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="StandardsSubscription-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/standardsSubscription.ts#L33">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#StandardsSubscriptionState'>StandardsSubscriptionState</a>, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#StandardsSubscription'>StandardsSubscription</a></pre>


Get an existing StandardsSubscription resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="StandardsSubscription-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L14">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="StandardsSubscription-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L107">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="StandardsSubscription-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L102">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</pre>
{{% md %}}

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="StandardsSubscription-standardsArn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/standardsSubscription.ts#L40">property <b>standardsArn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>standardsArn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The ARN of a standard - see below.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="StandardsSubscription-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L12">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>urn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</pre>
{{% md %}}

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="AccountArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/account.ts#L65">interface <b>AccountArgs</b></a>
</h2>
<div class="pdoc-module-contents">

The set of arguments for constructing a Account resource.

</div>
<h2 class="pdoc-module-header" id="AccountState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/account.ts#L59">interface <b>AccountState</b></a>
</h2>
<div class="pdoc-module-contents">

Input properties used for looking up and filtering Account resources.

</div>
<h2 class="pdoc-module-header" id="ProductSubscriptionArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/productSubscription.ts#L90">interface <b>ProductSubscriptionArgs</b></a>
</h2>
<div class="pdoc-module-contents">

The set of arguments for constructing a ProductSubscription resource.

<h3 class="pdoc-member-header" id="ProductSubscriptionArgs-productArn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/productSubscription.ts#L94">property <b>productArn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>productArn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The ARN of the product that generates findings that you want to import into Security Hub - see below.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="ProductSubscriptionState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/productSubscription.ts#L76">interface <b>ProductSubscriptionState</b></a>
</h2>
<div class="pdoc-module-contents">

Input properties used for looking up and filtering ProductSubscription resources.

<h3 class="pdoc-member-header" id="ProductSubscriptionState-arn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/productSubscription.ts#L80">property <b>arn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>arn?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The ARN of a resource that represents your subscription to the product that generates the findings that you want to import into Security Hub.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="ProductSubscriptionState-productArn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/productSubscription.ts#L84">property <b>productArn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>productArn?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The ARN of the product that generates findings that you want to import into Security Hub - see below.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="StandardsSubscriptionArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/standardsSubscription.ts#L79">interface <b>StandardsSubscriptionArgs</b></a>
</h2>
<div class="pdoc-module-contents">

The set of arguments for constructing a StandardsSubscription resource.

<h3 class="pdoc-member-header" id="StandardsSubscriptionArgs-standardsArn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/standardsSubscription.ts#L83">property <b>standardsArn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>standardsArn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The ARN of a standard - see below.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="StandardsSubscriptionState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/standardsSubscription.ts#L69">interface <b>StandardsSubscriptionState</b></a>
</h2>
<div class="pdoc-module-contents">

Input properties used for looking up and filtering StandardsSubscription resources.

<h3 class="pdoc-member-header" id="StandardsSubscriptionState-standardsArn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/c8d00d99880b7be8b4e79c50d210e91a4e9a942b/sdk/nodejs/securityhub/standardsSubscription.ts#L73">property <b>standardsArn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>standardsArn?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>
{{% md %}}

The ARN of a standard - see below.

{{% /md %}}
</div>
</div>