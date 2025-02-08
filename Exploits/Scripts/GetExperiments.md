# Experiments & Developer Options and more
```js
webpackChunkdiscord_app.push([[0], {}, (e) => { module = Object.values(e.c).find(x => x?.exports?.default?.getUsers).exports.default; }]);
nodes = Object.values(module._dispatcher._actionHandlers._dependencyGraph.nodes);
try { nodes.find(x => x.name == "ExperimentStore").actionHandler["OVERLAY_INITIALIZE"]({ user: { flags: 1 } }); } catch (e) { }
original = [module.getCurrentUser, module.getNonImpersonatedCurrentUser];
module.getCurrentUser = module.getNonImpersonatedCurrentUser = () => ({ isStaff: () => true });
nodes.find(x => x.name == "DeveloperExperimentStore").actionHandler["OVERLAY_INITIALIZE"]();
[module.getCurrentUser, module.getNonImpersonatedCurrentUser] = original;
```

