<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-server](./kibana-plugin-server.md) &gt; [PluginsServiceSetup](./kibana-plugin-server.pluginsservicesetup.md)

## PluginsServiceSetup interface


<b>Signature:</b>

```typescript
export interface PluginsServiceSetup 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [contracts](./kibana-plugin-server.pluginsservicesetup.contracts.md) | <code>Map&lt;PluginName, unknown&gt;</code> |  |
|  [uiPlugins](./kibana-plugin-server.pluginsservicesetup.uiplugins.md) | <code>{</code><br/><code>        internal: Map&lt;PluginName, InternalPluginInfo&gt;;</code><br/><code>        public: Map&lt;PluginName, DiscoveredPlugin&gt;;</code><br/><code>        browserConfigs: Map&lt;PluginName, Observable&lt;unknown&gt;&gt;;</code><br/><code>    }</code> |  |
