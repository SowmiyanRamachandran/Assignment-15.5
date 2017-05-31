name := "WordCount"
 
version := "1.0"
 
scalaVersion := "2.11.6"
 
scalacOptions += "-target:jvm-1.8"
 
publishMavenStyle := true
 
//dependencies for Hadoop program
 
libraryDependencies += "org.apache.hadoop" % "hadoop-mapreduce-client-core" % "2.7.1"
 
libraryDependencies += "org.apache.hadoop" % "hadoop-common" % "2.7.1"
 
javacOptions in (Compile, compile) ++= Seq("-source", "1.8", "-target", "1.8", "-g:lines")
 
mainClass in (Compile,run) := Some("WordCount")  //specifying fully qualified path of main class
 
crossPaths := false
 
autoScalaLibrary := false  //runs a pure java program
 
resolvers += Resolver.file("Frozen IVY2 Cache Dependences", file("/home/luis/.ivy2/cache")) (Resolver.ivyStylePatterns) ivys "/home/luis/.ivy2/cache/[organisation]/[module]/ivy-[revision].xml"  artifacts  "/home/luis/.ivy2/cache/[organisation]/[module]/[type]s/[module]-[revision].[type]"
