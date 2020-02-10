# Commons SpringBoot Parent

Maven parent project for all hdsdi3g' SpringBoot modules

Just add

```
	<parent>
		<groupId>tv.hd3g.commons</groupId>
		<artifactId>parent</artifactId>
		<version><!-- specify version  --></version>
		<relativePath />
	</parent>
```

in your pom.xml with the version you want to link from https://github.com/hdsdi3g/parent/releases.

If you need the persistence (JPA/MySQL) tools, use `parent-persistence` artifactId.

