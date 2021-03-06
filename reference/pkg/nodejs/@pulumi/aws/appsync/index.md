---
title: Module appsync
---

<a href="../index.html">@pulumi/aws</a> &gt; appsync

<h2 class="pdoc-module-header">Index</h2>

* <a href="#ApiKey">class ApiKey</a>
* <a href="#DataSource">class DataSource</a>
* <a href="#GraphQLApi">class GraphQLApi</a>
* <a href="#ApiKeyArgs">interface ApiKeyArgs</a>
* <a href="#ApiKeyState">interface ApiKeyState</a>
* <a href="#DataSourceArgs">interface DataSourceArgs</a>
* <a href="#DataSourceState">interface DataSourceState</a>
* <a href="#GraphQLApiArgs">interface GraphQLApiArgs</a>
* <a href="#GraphQLApiState">interface GraphQLApiState</a>

<a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts">appsync/apiKey.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts">appsync/dataSource.ts</a> <a href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts">appsync/graphQLApi.ts</a> 


<h2 class="pdoc-module-header" id="ApiKey">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L10">class ApiKey</a>
</h2>

Provides an AppSync API Key.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L38">constructor</a>
</h3>

```typescript
new ApiKey(name: string, args: ApiKeyArgs, opts?: pulumi.CustomResourceOptions)
```


Create a ApiKey resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L19">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: ApiKeyState): ApiKey
```


Get an existing ApiKey resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L26">property apiId</a>
</h3>

```typescript
public apiId: pulumi.Output<string>;
```


The ID of the associated AppSync API

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L30">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


The API key description. Defaults to "Managed by Terraform".

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L34">property expires</a>
</h3>

```typescript
public expires: pulumi.Output<string | undefined>;
```


RFC3339 string representation of the expiry date. Rounded down to nearest hour. By default, it is 7 days from the date of creation.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L38">property key</a>
</h3>

```typescript
public key: pulumi.Output<string>;
```


The API key

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="DataSource">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L10">class DataSource</a>
</h2>

Provides an AppSync DataSource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L62">constructor</a>
</h3>

```typescript
new DataSource(name: string, args: DataSourceArgs, opts?: pulumi.CustomResourceOptions)
```


Create a DataSource resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L19">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: DataSourceState): DataSource
```


Get an existing DataSource resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L26">property apiId</a>
</h3>

```typescript
public apiId: pulumi.Output<string>;
```


The API ID for the GraphQL API for the DataSource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L30">property arn</a>
</h3>

```typescript
public arn: pulumi.Output<string>;
```


The ARN

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L34">property description</a>
</h3>

```typescript
public description: pulumi.Output<string | undefined>;
```


A description of the DataSource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L38">property dynamodbConfig</a>
</h3>

```typescript
public dynamodbConfig: pulumi.Output<{ ... } | undefined>;
```


DynamoDB settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L42">property elasticsearchConfig</a>
</h3>

```typescript
public elasticsearchConfig: pulumi.Output<{ ... } | undefined>;
```


Amazon Elasticsearch settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L46">property httpConfig</a>
</h3>

```typescript
public httpConfig: pulumi.Output<{ ... } | undefined>;
```


HTTP settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L50">property lambdaConfig</a>
</h3>

```typescript
public lambdaConfig: pulumi.Output<{ ... } | undefined>;
```


AWS Lambda settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L54">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A user-supplied name for the DataSource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L58">property serviceRoleArn</a>
</h3>

```typescript
public serviceRoleArn: pulumi.Output<string | undefined>;
```


The IAM service role ARN for the data source.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L62">property type</a>
</h3>

```typescript
public type: pulumi.Output<string>;
```


The type of the DataSource. Valid values: `AWS_LAMBDA`, `AMAZON_DYNAMODB`, `AMAZON_ELASTICSEARCH`, `HTTP`, `NONE`.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h2 class="pdoc-module-header" id="GraphQLApi">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L10">class GraphQLApi</a>
</h2>

Provides an AppSync GraphQL API.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L50">constructor</a>
</h3>

```typescript
new GraphQLApi(name: string, args: GraphQLApiArgs, opts?: pulumi.CustomResourceOptions)
```


Create a GraphQLApi resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L19">method get</a>
</h3>

```typescript
public static get(name: string, id: pulumi.Input<pulumi.ID>, state?: GraphQLApiState): GraphQLApi
```


Get an existing GraphQLApi resource's state with the given name, ID, and optional extra
properties used to qualify the lookup.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L13">method getProvider</a>
</h3>

```typescript
getProvider(moduleMember: string): ProviderResource | undefined
```

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L85">method isInstance</a>
</h3>

```typescript
static isInstance(obj: any): boolean
```


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L26">property arn</a>
</h3>

```typescript
public arn: pulumi.Output<string>;
```


The ARN

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L30">property authenticationType</a>
</h3>

```typescript
public authenticationType: pulumi.Output<string>;
```


The authentication type. Valid values: `API_KEY`, `AWS_IAM`, `AMAZON_COGNITO_USER_POOLS`, `OPENID_CONNECT`

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L80">property id</a>
</h3>

```typescript
id: Output<ID>;
```


id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L34">property logConfig</a>
</h3>

```typescript
public logConfig: pulumi.Output<{ ... } | undefined>;
```


Nested argument containing logging configuration. Defined below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L38">property name</a>
</h3>

```typescript
public name: pulumi.Output<string>;
```


A user-supplied name for the GraphqlApi.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L42">property openidConnectConfig</a>
</h3>

```typescript
public openidConnectConfig: pulumi.Output<{ ... } | undefined>;
```


Nested argument containing OpenID Connect configuration. Defined below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L46">property uris</a>
</h3>

```typescript
public uris: pulumi.Output<{ ... }>;
```


Map of URIs associated with the API. e.g. `uris["GRAPHQL"] = https://ID.appsync-api.REGION.amazonaws.com/graphql`

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L11">property urn</a>
</h3>

```typescript
urn: Output<URN>;
```


urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L50">property userPoolConfig</a>
</h3>

```typescript
public userPoolConfig: pulumi.Output<{ ... } | undefined>;
```


The Amazon Cognito User Pool configuration. Defined below.

<h2 class="pdoc-module-header" id="ApiKeyArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L95">interface ApiKeyArgs</a>
</h2>

The set of arguments for constructing a ApiKey resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L99">property apiId</a>
</h3>

```typescript
apiId: pulumi.Input<string>;
```


The ID of the associated AppSync API

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L103">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


The API key description. Defaults to "Managed by Terraform".

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L107">property expires</a>
</h3>

```typescript
expires?: pulumi.Input<string>;
```


RFC3339 string representation of the expiry date. Rounded down to nearest hour. By default, it is 7 days from the date of creation.

<h2 class="pdoc-module-header" id="ApiKeyState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L73">interface ApiKeyState</a>
</h2>

Input properties used for looking up and filtering ApiKey resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L77">property apiId</a>
</h3>

```typescript
apiId?: pulumi.Input<string>;
```


The ID of the associated AppSync API

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L81">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


The API key description. Defaults to "Managed by Terraform".

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L85">property expires</a>
</h3>

```typescript
expires?: pulumi.Input<string>;
```


RFC3339 string representation of the expiry date. Rounded down to nearest hour. By default, it is 7 days from the date of creation.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/apiKey.ts#L89">property key</a>
</h3>

```typescript
key?: pulumi.Input<string>;
```


The API key

<h2 class="pdoc-module-header" id="DataSourceArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L158">interface DataSourceArgs</a>
</h2>

The set of arguments for constructing a DataSource resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L162">property apiId</a>
</h3>

```typescript
apiId: pulumi.Input<string>;
```


The API ID for the GraphQL API for the DataSource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L166">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


A description of the DataSource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L170">property dynamodbConfig</a>
</h3>

```typescript
dynamodbConfig?: pulumi.Input<{ ... }>;
```


DynamoDB settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L174">property elasticsearchConfig</a>
</h3>

```typescript
elasticsearchConfig?: pulumi.Input<{ ... }>;
```


Amazon Elasticsearch settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L178">property httpConfig</a>
</h3>

```typescript
httpConfig?: pulumi.Input<{ ... }>;
```


HTTP settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L182">property lambdaConfig</a>
</h3>

```typescript
lambdaConfig?: pulumi.Input<{ ... }>;
```


AWS Lambda settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L186">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A user-supplied name for the DataSource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L190">property serviceRoleArn</a>
</h3>

```typescript
serviceRoleArn?: pulumi.Input<string>;
```


The IAM service role ARN for the data source.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L194">property type</a>
</h3>

```typescript
type: pulumi.Input<string>;
```


The type of the DataSource. Valid values: `AWS_LAMBDA`, `AMAZON_DYNAMODB`, `AMAZON_ELASTICSEARCH`, `HTTP`, `NONE`.

<h2 class="pdoc-module-header" id="DataSourceState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L112">interface DataSourceState</a>
</h2>

Input properties used for looking up and filtering DataSource resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L116">property apiId</a>
</h3>

```typescript
apiId?: pulumi.Input<string>;
```


The API ID for the GraphQL API for the DataSource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L120">property arn</a>
</h3>

```typescript
arn?: pulumi.Input<string>;
```


The ARN

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L124">property description</a>
</h3>

```typescript
description?: pulumi.Input<string>;
```


A description of the DataSource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L128">property dynamodbConfig</a>
</h3>

```typescript
dynamodbConfig?: pulumi.Input<{ ... }>;
```


DynamoDB settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L132">property elasticsearchConfig</a>
</h3>

```typescript
elasticsearchConfig?: pulumi.Input<{ ... }>;
```


Amazon Elasticsearch settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L136">property httpConfig</a>
</h3>

```typescript
httpConfig?: pulumi.Input<{ ... }>;
```


HTTP settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L140">property lambdaConfig</a>
</h3>

```typescript
lambdaConfig?: pulumi.Input<{ ... }>;
```


AWS Lambda settings. See below

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L144">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A user-supplied name for the DataSource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L148">property serviceRoleArn</a>
</h3>

```typescript
serviceRoleArn?: pulumi.Input<string>;
```


The IAM service role ARN for the data source.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/dataSource.ts#L152">property type</a>
</h3>

```typescript
type?: pulumi.Input<string>;
```


The type of the DataSource. Valid values: `AWS_LAMBDA`, `AMAZON_DYNAMODB`, `AMAZON_ELASTICSEARCH`, `HTTP`, `NONE`.

<h2 class="pdoc-module-header" id="GraphQLApiArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L125">interface GraphQLApiArgs</a>
</h2>

The set of arguments for constructing a GraphQLApi resource.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L129">property authenticationType</a>
</h3>

```typescript
authenticationType: pulumi.Input<string>;
```


The authentication type. Valid values: `API_KEY`, `AWS_IAM`, `AMAZON_COGNITO_USER_POOLS`, `OPENID_CONNECT`

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L133">property logConfig</a>
</h3>

```typescript
logConfig?: pulumi.Input<{ ... }>;
```


Nested argument containing logging configuration. Defined below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L137">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A user-supplied name for the GraphqlApi.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L141">property openidConnectConfig</a>
</h3>

```typescript
openidConnectConfig?: pulumi.Input<{ ... }>;
```


Nested argument containing OpenID Connect configuration. Defined below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L145">property userPoolConfig</a>
</h3>

```typescript
userPoolConfig?: pulumi.Input<{ ... }>;
```


The Amazon Cognito User Pool configuration. Defined below.

<h2 class="pdoc-module-header" id="GraphQLApiState">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L91">interface GraphQLApiState</a>
</h2>

Input properties used for looking up and filtering GraphQLApi resources.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L95">property arn</a>
</h3>

```typescript
arn?: pulumi.Input<string>;
```


The ARN

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L99">property authenticationType</a>
</h3>

```typescript
authenticationType?: pulumi.Input<string>;
```


The authentication type. Valid values: `API_KEY`, `AWS_IAM`, `AMAZON_COGNITO_USER_POOLS`, `OPENID_CONNECT`

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L103">property logConfig</a>
</h3>

```typescript
logConfig?: pulumi.Input<{ ... }>;
```


Nested argument containing logging configuration. Defined below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L107">property name</a>
</h3>

```typescript
name?: pulumi.Input<string>;
```


A user-supplied name for the GraphqlApi.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L111">property openidConnectConfig</a>
</h3>

```typescript
openidConnectConfig?: pulumi.Input<{ ... }>;
```


Nested argument containing OpenID Connect configuration. Defined below.

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L115">property uris</a>
</h3>

```typescript
uris?: pulumi.Input<{ ... }>;
```


Map of URIs associated with the API. e.g. `uris["GRAPHQL"] = https://ID.appsync-api.REGION.amazonaws.com/graphql`

<h3 class="pdoc-member-header">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-aws/blob/master/sdk/nodejs/appsync/graphQLApi.ts#L119">property userPoolConfig</a>
</h3>

```typescript
userPoolConfig?: pulumi.Input<{ ... }>;
```


The Amazon Cognito User Pool configuration. Defined below.

