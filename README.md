# mill-sonatype-central-portal-example

Example of publishing a library through Sonatype Central Portal with Mill.

https://mill-build.org/mill/contrib/sonatypecentral.html

```shell
$VERSION="0.0.3-SNAPSHOT"
git commit --allow-empty -m "Release $VERSION"
git tag -a $VERSION -m "Release $VERSION"
git push --atomic origin main --tags
```

