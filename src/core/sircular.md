util/index -> observer/index -> observer/array
observer/dep -> observer/watcher
observer/watcher -> observer/scheduler
util/index -> observer/index -> observer/dep -> observer/watcher -> observer/scheduler
util/index -> observer/index -> observer/dep -> observer/watcher
util/index -> observer/index -> observer/dep
util/index -> observer/index
util/index -> util/options -> instance/index -> instance/events
util/index -> util/options -> instance/index -> instance/init -> instance/lifecycle -> instance/render
util/index -> util/options -> instance/index -> instance/init -> instance/lifecycle -> instance/render -> vdom/create-element
instance/init -> instance/lifecycle -> instance/render -> vdom/create-element -> vdom/create-component
instance/lifecycle -> instance/render -> vdom/create-element -> vdom/create-component
instance/render -> vdom/create-element -> vdom/create-component
util/index -> util/options -> instance/index -> instance/init -> instance/lifecycle -> instance/render -> vdom/create-element -> vdom/create-component
vdom/create-element -> vdom/create-component
util/index -> util/options -> instance/index -> instance/init -> instance/lifecycle
util/index -> util/options -> instance/index -> instance/init -> instance/proxy
util/index -> util/options -> instance/index -> instance/init -> instance/state
util/index -> util/options -> instance/index -> instance/init
util/index -> util/options -> instance/index
