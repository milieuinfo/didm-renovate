# DIDM Renovate

Check de package.json voor alle `milieuinfo/webcomponent*` repositories op updates.
Meer info op https://renovatebot.com.

Run starten kan via:

```
docker run 
--volume ${PWD}/renovate.json:/usr/src/app/renovate.json 
-e RENOVATE_TOKEN=955945622c6d758b064e9449c089988a5de4bbe8 
-e RENOVATE_CONFIG_FILE=/usr/src/app/renovate.json 
-e HTTP_PROXY=http://forwardproxy-pr-build.lb.cumuli.be:3128
-e HTTPS_PROXY=http://forwardproxy-pr-build.lb.cumuli.be:3128
renovate/renovate
```
