---
title: "Module devspace"
linktitle: "devspace"
meta_desc: "Explore members of the devspace module in the @pulumi/azure package."
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->


> This provider is a derived work of the [Terraform Provider](https://github.com/terraform-providers/terraform-provider-azurerm)
> distributed under [MPL 2.0](https://www.mozilla.org/en-US/MPL/2.0/). If you encounter a bug or missing feature,
> first check the [`pulumi/pulumi-azure` repo](https://github.com/pulumi/pulumi-azure/issues); however, if that doesn't turn up anything,
> please consult the source [`terraform-providers/terraform-provider-azurerm` repo](https://github.com/terraform-providers/terraform-provider-azurerm/issues).





<h3>Resources</h3>
<ul class="api">
    <li><a href="#Controller"><span class="symbol resource"></span>Controller</a></li>
</ul>


<h3>Others</h3>
<ul class="api">
    <li><a href="#ControllerArgs"><span class="symbol api"></span>ControllerArgs</a></li>
    <li><a href="#ControllerState"><span class="symbol api"></span>ControllerState</a></li>
</ul>


<h2 id="resources">Resources</h2>
<h3 class="pdoc-module-header" id="Controller" data-link-title="Controller">
    <a href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L14">
        Resource <strong>Controller</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>class</span> <span class='nx'>Controller</span> <span class='kr'>extends</span> <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResource'>CustomResource</a></code></pre>

Manages a DevSpace Controller.

> This content is derived from https://github.com/terraform-providers/terraform-provider-azurerm/blob/master/website/docs/r/devspace_controller.html.markdown.

<h4 class="pdoc-member-header" id="Controller-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L76"> <b>constructor</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span><span class='kd'>new</span> Controller(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#ControllerArgs'>ControllerArgs</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</code></pre>


Create a Controller resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h4 class="pdoc-member-header" id="Controller-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L23">method <b>get</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>pulumi.ID</a>&gt;, state?: <a href='#ControllerState'>ControllerState</a>, opts?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>): <a href='#Controller'>Controller</a></code></pre>


Get an existing Controller resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h4 class="pdoc-member-header" id="Controller-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L14">method <b>getProvider</b></a>
</h4>


<pre class="highlight"><code><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ProviderResource'>ProviderResource</a> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></code></pre>

<h4 class="pdoc-member-header" id="Controller-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L34">method <b>isInstance</b></a>
</h4>


<pre class="highlight"><code><span class='kd'>public static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></code></pre>


Returns true if the given object is an instance of Controller.  This is designed to work even
when multiple copies of the Pulumi SDK have been loaded into the same process.

<h4 class="pdoc-member-header" id="Controller-dataPlaneFqdn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L44">property <b>dataPlaneFqdn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>dataPlaneFqdn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

DNS name for accessing DataPlane services.

<h4 class="pdoc-member-header" id="Controller-hostSuffix">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L48">property <b>hostSuffix</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>hostSuffix: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The host suffix for the DevSpace Controller.

<h4 class="pdoc-member-header" id="Controller-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L14">property <b>id</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>id: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#ID'>ID</a>&gt;;</code></pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h4 class="pdoc-member-header" id="Controller-location">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L52">property <b>location</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>location: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the supported location where the DevSpace Controller should exist. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="Controller-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L56">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>name: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the name of the DevSpace Controller. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="Controller-resourceGroupName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L60">property <b>resourceGroupName</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>resourceGroupName: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The name of the resource group under which the DevSpace Controller resource has to be created. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="Controller-sku">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L64">property <b>sku</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>sku: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/azure/types/output/#ControllerSku'>outputs.devspace.ControllerSku</a>&gt;;</code></pre>

A `sku` block as documented below. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="Controller-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L68">property <b>tags</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>tags: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</code></pre>

A mapping of tags to assign to the resource.

<h4 class="pdoc-member-header" id="Controller-targetContainerHostCredentialsBase64">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L72">property <b>targetContainerHostCredentialsBase64</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>targetContainerHostCredentialsBase64: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Base64 encoding of `kubeConfigRaw` of Azure Kubernetes Service cluster. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="Controller-targetContainerHostResourceId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L76">property <b>targetContainerHostResourceId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'>public </span>targetContainerHostResourceId: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The resource id of Azure Kubernetes Service cluster. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="Controller-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L14">property <b>urn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>urn: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Output'>Output</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#URN'>URN</a>&gt;;</code></pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.



<h2 id="apis">Others</h2>
<h3 class="pdoc-module-header" id="ControllerArgs" data-link-title="ControllerArgs">
    <a href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L179">
        interface <strong>ControllerArgs</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>ControllerArgs</span></code></pre>

The set of arguments for constructing a Controller resource.

<h4 class="pdoc-member-header" id="ControllerArgs-location">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L183">property <b>location</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>location?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the supported location where the DevSpace Controller should exist. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="ControllerArgs-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L187">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the name of the DevSpace Controller. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="ControllerArgs-resourceGroupName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L191">property <b>resourceGroupName</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>resourceGroupName: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The name of the resource group under which the DevSpace Controller resource has to be created. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="ControllerArgs-sku">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L195">property <b>sku</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>sku: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ControllerSku'>inputs.devspace.ControllerSku</a>&gt;;</code></pre>

A `sku` block as documented below. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="ControllerArgs-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L199">property <b>tags</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>tags?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</code></pre>

A mapping of tags to assign to the resource.

<h4 class="pdoc-member-header" id="ControllerArgs-targetContainerHostCredentialsBase64">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L203">property <b>targetContainerHostCredentialsBase64</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>targetContainerHostCredentialsBase64: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Base64 encoding of `kubeConfigRaw` of Azure Kubernetes Service cluster. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="ControllerArgs-targetContainerHostResourceId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L207">property <b>targetContainerHostResourceId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>targetContainerHostResourceId: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The resource id of Azure Kubernetes Service cluster. Changing this forces a new resource to be created.

<h3 class="pdoc-module-header" id="ControllerState" data-link-title="ControllerState">
    <a href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L137">
        interface <strong>ControllerState</strong>
    </a>
</h3>

<pre class="highlight"><code><span class='kr'>interface</span> <span class='nx'>ControllerState</span></code></pre>

Input properties used for looking up and filtering Controller resources.

<h4 class="pdoc-member-header" id="ControllerState-dataPlaneFqdn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L141">property <b>dataPlaneFqdn</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>dataPlaneFqdn?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

DNS name for accessing DataPlane services.

<h4 class="pdoc-member-header" id="ControllerState-hostSuffix">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L145">property <b>hostSuffix</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>hostSuffix?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The host suffix for the DevSpace Controller.

<h4 class="pdoc-member-header" id="ControllerState-location">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L149">property <b>location</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>location?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the supported location where the DevSpace Controller should exist. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="ControllerState-name">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L153">property <b>name</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>name?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Specifies the name of the DevSpace Controller. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="ControllerState-resourceGroupName">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L157">property <b>resourceGroupName</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>resourceGroupName?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The name of the resource group under which the DevSpace Controller resource has to be created. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="ControllerState-sku">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L161">property <b>sku</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>sku?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='/docs/reference/pkg/nodejs/pulumi/azure/types/input/#ControllerSku'>inputs.devspace.ControllerSku</a>&gt;;</code></pre>

A `sku` block as documented below. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="ControllerState-tags">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L165">property <b>tags</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>tags?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;{[key: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>]: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>}&gt;;</code></pre>

A mapping of tags to assign to the resource.

<h4 class="pdoc-member-header" id="ControllerState-targetContainerHostCredentialsBase64">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L169">property <b>targetContainerHostCredentialsBase64</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>targetContainerHostCredentialsBase64?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

Base64 encoding of `kubeConfigRaw` of Azure Kubernetes Service cluster. Changing this forces a new resource to be created.

<h4 class="pdoc-member-header" id="ControllerState-targetContainerHostResourceId">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-azure/blob/814aeefbe707f94356a8f21fc35e192ce8633607/sdk/nodejs/devspace/controller.ts#L173">property <b>targetContainerHostResourceId</b></a>
</h4>

<pre class="highlight"><code><span class='kd'></span>targetContainerHostResourceId?: <a href='/docs/reference/pkg/nodejs/pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</code></pre>

The resource id of Azure Kubernetes Service cluster. Changing this forces a new resource to be created.

