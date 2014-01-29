RTBkit Quickboard

This is a simple dashboarding system for RTBkit. Simply load up the HTML file in a browser and fill in your Graphite host and whatever prefix your RTBkit keys have in Graphite. A demo is available (securely, as all communication is between your browser and your Graphite) at [http://rtbkit.github.io/quickboard](http://rtbkit.github.io/quickboard).

The recommended key layout in Graphite is `<installation>.<location>.<server>.<service>` so keys under `xyz.us_east.rtb1` would correspond to metrics from server `rtb1` in the `us_east` location for the `xyz` installation. If you follow this convention, then `xyz.*.*` is the right value to use for the `prefix` field in this dashboard to see metrics for the `xyz` installation.