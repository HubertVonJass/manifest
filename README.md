# manifest
manifest

after repo syncing the main Evolution-X repo (https://github.com/Evolution-X), open this file:
.repo/manifests/default.xml

and add this to the bottom, right under the LineageOS piece but before the </manifest> line
"-- HubertVonJass -->
  <include name="hughjass.xml""

and add the hughjass.xml file from this repo to the same folder (.repo/manifests)
