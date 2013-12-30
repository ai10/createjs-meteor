Package.describe({
  summary: 'CreateJS packaged for Meteor'
});

Package.on_use(function (api) {
  api.add_files('lib/createjs-2013.09.25.min.js', 'client');

  // for backward compat before Meteor linker changes
  if (typeof api.export !== 'undefined') api.export('createjs');
});
