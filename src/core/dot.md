digraph G {
  "components/index";
  "components/keep-alive";
  "config";
  "global-api/assets";
  "util/index";
  "global-api/extend";
  "global-api/index";
  "global-api/mixin";
  "global-api/use";
  "observer/index";
  "index";
  "instance/index";
  "instance/events";
  "vdom/helpers/index";
  "instance/init";
  "instance/lifecycle";
  "instance/render";
  "instance/state";
  "instance/proxy";
  "observer/watcher";
  "vdom/vnode";
  "vdom/create-element";
  "observer/dep";
  "observer/array";
  "observer/scheduler";
  "util/debug";
  "util/env";
  "util/lang";
  "util/options";
  "util/props";
  "vdom/create-component";
  "vdom/helpers/merge-hook";
  "vdom/helpers/normalize-children";
  "vdom/helpers/update-listeners";
  "components/index" -> "components/keep-alive";
  "global-api/assets" -> "config";
  "global-api/assets" -> "util/index";
  "global-api/extend" -> "config";
  "global-api/extend" -> "util/index";
  "global-api/index" -> "components/index";
  "global-api/index" -> "config";
  "global-api/index" -> "global-api/assets";
  "global-api/index" -> "global-api/extend";
  "global-api/index" -> "global-api/mixin";
  "global-api/index" -> "global-api/use";
  "global-api/index" -> "observer/index";
  "global-api/index" -> "util/index";
  "global-api/mixin" -> "util/index";
  "global-api/use" -> "util/index";
  "index" -> "config";
  "index" -> "global-api/index";
  "index" -> "instance/index";
  "instance/events" -> "util/index";
  "instance/events" -> "vdom/helpers/index";
  "instance/index" -> "instance/events";
  "instance/index" -> "instance/init";
  "instance/index" -> "instance/lifecycle";
  "instance/index" -> "instance/render";
  "instance/index" -> "instance/state";
  "instance/index" -> "util/index";
  "instance/init" -> "instance/events";
  "instance/init" -> "instance/lifecycle";
  "instance/init" -> "instance/proxy";
  "instance/init" -> "instance/render";
  "instance/init" -> "instance/state";
  "instance/init" -> "util/index";
  "instance/lifecycle" -> "instance/render";
  "instance/lifecycle" -> "observer/index";
  "instance/lifecycle" -> "observer/watcher";
  "instance/lifecycle" -> "util/index";
  "instance/lifecycle" -> "vdom/vnode";
  "instance/proxy" -> "util/index";
  "instance/render" -> "config";
  "instance/render" -> "util/index";
  "instance/render" -> "vdom/create-element";
  "instance/render" -> "vdom/helpers/index";
  "instance/render" -> "vdom/vnode";
  "instance/state" -> "observer/dep";
  "instance/state" -> "observer/index";
  "instance/state" -> "observer/watcher";
  "instance/state" -> "util/index";
  "observer/array" -> "util/index";
  "observer/dep" -> "observer/watcher";
  "observer/dep" -> "util/index";
  "observer/index" -> "config";
  "observer/index" -> "observer/array";
  "observer/index" -> "observer/dep";
  "observer/index" -> "util/index";
  "observer/scheduler" -> "config";
  "observer/scheduler" -> "observer/watcher";
  "observer/scheduler" -> "util/index";
  "observer/watcher" -> "config";
  "observer/watcher" -> "observer/dep";
  "observer/watcher" -> "observer/scheduler";
  "observer/watcher" -> "util/index";
  "util/debug" -> "config";
  "util/index" -> "observer/index";
  "util/index" -> "util/debug";
  "util/index" -> "util/env";
  "util/index" -> "util/lang";
  "util/index" -> "util/options";
  "util/index" -> "util/props";
  "util/options" -> "config";
  "util/options" -> "instance/index";
  "util/options" -> "observer/index";
  "util/options" -> "util/debug";
  "util/props" -> "observer/index";
  "util/props" -> "util/debug";
  "vdom/create-component" -> "instance/init";
  "vdom/create-component" -> "instance/lifecycle";
  "vdom/create-component" -> "instance/render";
  "vdom/create-component" -> "util/index";
  "vdom/create-component" -> "vdom/create-element";
  "vdom/create-component" -> "vdom/helpers/index";
  "vdom/create-component" -> "vdom/vnode";
  "vdom/create-element" -> "config";
  "vdom/create-element" -> "util/index";
  "vdom/create-element" -> "vdom/create-component";
  "vdom/create-element" -> "vdom/helpers/index";
  "vdom/create-element" -> "vdom/vnode";
  "vdom/helpers/index" -> "vdom/helpers/merge-hook";
  "vdom/helpers/index" -> "vdom/helpers/normalize-children";
  "vdom/helpers/index" -> "vdom/helpers/update-listeners";
}