---
title: Module storage/v1alpha1
aliases:
    - "/reference/pkg/nodejs/@pulumi/kubernetes/storage/v1alpha1/"
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../../">@pulumi/kubernetes</a> &gt; <a href="../">storage</a> &gt; v1alpha1

<div class="toggleVisible">
<div class="collapsed">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents">
<ul>
<li><a href="#VolumeAttachment">class VolumeAttachment</a></li>
<li><a href="#VolumeAttachmentList">class VolumeAttachmentList</a></li>
</ul>

<a href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachment.ts">storage/v1alpha1/VolumeAttachment.ts</a> <a href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachmentList.ts">storage/v1alpha1/VolumeAttachmentList.ts</a> 
</div>
</div>
</div>


<h2 class="pdoc-module-header" id="VolumeAttachment">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachment.ts#L14">class <b>VolumeAttachment</b></a>
</h2>
<div class="pdoc-module-contents">
<pre class="highlight"><span class='kd'>extends</span> <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

VolumeAttachment captures the intent to attach or detach the specified volume to/from the
specified node.

VolumeAttachment objects are non-namespaced.

<h3 class="pdoc-member-header" id="VolumeAttachment-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachment.ts#L66"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> VolumeAttachment(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args?: inputApi.storage.v1alpha1.VolumeAttachment, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a storage.v1alpha1.VolumeAttachment resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachment-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachment.ts#L61">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#VolumeAttachment'>VolumeAttachment</a></pre>


Get the state of an existing `VolumeAttachment` resource, as identified by `id`.
Typically this ID  is of the form <namespace>/<name>; if <namespace> is omitted, then (per
Kubernetes convention) the ID becomes default/<name>.

Pulumi will keep track of this resource using `name` as the Pulumi ID.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachment-getInputs">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachment.ts#L65">method <b>getInputs</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public </span>getInputs(): inputApi.storage.v1alpha1.VolumeAttachment</pre>

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachment-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L14">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachment-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L107">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachment-apiVersion">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachment.ts#L21">property <b>apiVersion</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>apiVersion: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='s2'>"storage.k8s.io/v1alpha1"</span>&gt;;</pre>
{{% md %}}

APIVersion defines the versioned schema of this representation of an object. Servers should
convert recognized schemas to the latest internal value, and may reject unrecognized
values. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#resources

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachment-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L102">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</pre>
{{% md %}}

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachment-kind">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachment.ts#L29">property <b>kind</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>kind: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='s2'>"VolumeAttachment"</span>&gt;;</pre>
{{% md %}}

Kind is a string value representing the REST resource this object represents. Servers may
infer this from the endpoint the client submits requests to. Cannot be updated. In
CamelCase. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#types-kinds

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachment-metadata">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachment.ts#L35">property <b>metadata</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>metadata: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;outputApi.meta.v1.ObjectMeta&gt;;</pre>
{{% md %}}

Standard object metadata. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#metadata

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachment-spec">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachment.ts#L41">property <b>spec</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>spec: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;outputApi.storage.v1alpha1.VolumeAttachmentSpec&gt;;</pre>
{{% md %}}

Specification of the desired attach/detach volume behavior. Populated by the Kubernetes
system.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachment-status">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachment.ts#L47">property <b>status</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>status: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;outputApi.storage.v1alpha1.VolumeAttachmentStatus&gt;;</pre>
{{% md %}}

Status of the VolumeAttachment request. Populated by the entity completing the attach or
detach operation, i.e. the external-attacher.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachment-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L12">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>urn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</pre>
{{% md %}}

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

{{% /md %}}
</div>
</div>
<h2 class="pdoc-module-header" id="VolumeAttachmentList">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachmentList.ts#L11">class <b>VolumeAttachmentList</b></a>
</h2>
<div class="pdoc-module-contents">
<pre class="highlight"><span class='kd'>extends</span> <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

VolumeAttachmentList is a collection of VolumeAttachment objects.

<h3 class="pdoc-member-header" id="VolumeAttachmentList-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachmentList.ts#L56"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> VolumeAttachmentList(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args?: inputApi.storage.v1alpha1.VolumeAttachmentList, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a storage.v1alpha1.VolumeAttachmentList resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachmentList-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachmentList.ts#L51">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, opts?: <a href='/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#VolumeAttachmentList'>VolumeAttachmentList</a></pre>


Get the state of an existing `VolumeAttachmentList` resource, as identified by `id`.
Typically this ID  is of the form <namespace>/<name>; if <namespace> is omitted, then (per
Kubernetes convention) the ID becomes default/<name>.

Pulumi will keep track of this resource using `name` as the Pulumi ID.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachmentList-getInputs">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachmentList.ts#L55">method <b>getInputs</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>public </span>getInputs(): inputApi.storage.v1alpha1.VolumeAttachmentList</pre>

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachmentList-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L14">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachmentList-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L107">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents">
{{% md %}}

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachmentList-apiVersion">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachmentList.ts#L18">property <b>apiVersion</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>apiVersion: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='s2'>"storage.k8s.io/v1alpha1"</span>&gt;;</pre>
{{% md %}}

APIVersion defines the versioned schema of this representation of an object. Servers should
convert recognized schemas to the latest internal value, and may reject unrecognized
values. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#resources

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachmentList-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L102">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>id: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</pre>
{{% md %}}

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachmentList-items">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachmentList.ts#L23">property <b>items</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>items: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;outputApi.storage.v1alpha1.VolumeAttachment[]&gt;;</pre>
{{% md %}}

Items is the list of VolumeAttachments

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachmentList-kind">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachmentList.ts#L31">property <b>kind</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>kind: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='s2'>"VolumeAttachmentList"</span>&gt;;</pre>
{{% md %}}

Kind is a string value representing the REST resource this object represents. Servers may
infer this from the endpoint the client submits requests to. Cannot be updated. In
CamelCase. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#types-kinds

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachmentList-metadata">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/storage/v1alpha1/VolumeAttachmentList.ts#L37">property <b>metadata</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'>public </span>metadata: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;outputApi.meta.v1.ListMeta&gt;;</pre>
{{% md %}}

Standard list metadata More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#metadata

{{% /md %}}
</div>
<h3 class="pdoc-member-header" id="VolumeAttachmentList-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/ff9e6550e366d1317a169380ac0aab19bd12bdd4/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L12">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents">
<pre class="highlight"><span class='kd'></span>urn: <a href='/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</pre>
{{% md %}}

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

{{% /md %}}
</div>
</div>