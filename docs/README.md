Hello this is a test.

<!--- transclusion start cjp8tfahl0000unn3jkc0om9e file fragment1.yml with regular expression [] DO NOT EDIT TRANSCLUDED TEXT, go to the source -->

```yml
---
- hosts: all
  tasks:
    - debug: msg="{{ lookup('env','BUILD_TAG') }}"
```

<!--- transclusion end cjp8tfahl0000unn3jkc0om9e file fragment1.yml with regular expression [] DO NOT EDIT TRANSCLUDED TEXT, go to the source -->

another thing

<!--- transclusion start cjp8tfahl0001unn3v1ggxdux file fragment2.scala with regular expression [(.*override final def descriptor = {([^{}]|(?R))*})] DO NOT EDIT TRANSCLUDED TEXT, go to the source -->

```scala
  override final def descriptor = {
    import Service._
    // @formatter:off
    named("hello-world").withCalls(
      restCall(Method.POST, "/api/hello-worlds", createHelloWorldWithSystemGeneratedId _),
      restCall(Method.POST, "/api/hello-worlds/:helloWorldId/create-hello-world", createHelloWorld _),
      //restCall(Method.POST, "/api/hello-worlds/:helloWorldId/destroy-hello-world", destroyHelloWorld _),
      //restCall(Method.POST, "/api/hello-worlds/:helloWorldId/improve-hello-world-description", improveHelloWorldDescription _),
      //restCall(Method.POST, "/api/hello-worlds/:helloWorldId/archive-hello-world", archiveHelloWorld _),
      //restCall(Method.POST, "/api/hello-worlds/:helloWorldId/unarchive-hello-world", unarchiveHelloWorld _),
//      pathCall("/api/hello-worlds/stream", streamHelloWorlds _),
      //restCall(Method.GET, "/api/hello-worlds/:helloWorldId", getHelloWorld _),
      //restCall(Method.GET, "/api/hello-worlds", getAllHelloWorlds _)
    )
      .withAutoAcl(true)
      .withExceptionSerializer(new DefaultExceptionSerializer(Environment.simple(mode = Mode.Prod)))
      .withTopics(
        topic("helloWorld-HelloWorldMessageBrokerEvent", this.helloWorldMessageBrokerEvents)
      )
    // @formatter:on
  }
```

<!--- transclusion end cjp8tfahl0001unn3v1ggxdux file fragment2.scala with regular expression [(.*override final def descriptor = {([^{}]|(?R))*})] DO NOT EDIT TRANSCLUDED TEXT, go to the source -->
