# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.125 ops/ms
Iteration   1: 5.915 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.915 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.076 ops/ms
Iteration   1: 12.374 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.374 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.274 ops/ms
Iteration   1: 10.267 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.267 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.109 ops/ms
Iteration   1: 3.665 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.665 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.409 ±(99.9%) 0.057 ms/op
Iteration   1: 3.057 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.057 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.207 ±(99.9%) 0.035 ms/op
Iteration   1: 2.063 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.063 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.722 ±(99.9%) 0.049 ms/op
Iteration   1: 3.095 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.095 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.616 ±(99.9%) 0.217 ms/op
Iteration   1: 8.332 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.332 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.024 ±(99.9%) 0.107 ms/op
Iteration   1: 3.302 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   7.938 ms/op
                 createUser·p0.999:  16.908 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9822
  mean =      3.302 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1328 
    [ 2.500,  3.750) = 6353 
    [ 3.750,  5.000) = 1786 
    [ 5.000,  6.250) = 148 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     17.236 ms/op
     p(99.9990) =     17.236 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.999 ±(99.9%) 0.061 ms/op
Iteration   1: 1.806 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   1.669 ms/op
                 existUser·p0.90:   2.236 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  22.527 ms/op
                 existUser·p0.9999: 23.666 ms/op
                 existUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17761
  mean =      1.806 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16874 
    [ 2.500,  5.000) = 804 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =     22.527 ms/op
     p(99.9900) =     23.666 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.981 ±(99.9%) 0.101 ms/op
Iteration   1: 2.992 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   2.826 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.670 ms/op
                 getUser·p0.999:  16.861 ms/op
                 getUser·p0.9999: 17.424 ms/op
                 getUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10690
  mean =      2.992 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 3172 
    [ 2.500,  3.750) = 6282 
    [ 3.750,  5.000) = 1040 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      6.670 ms/op
     p(99.9000) =     16.861 ms/op
     p(99.9900) =     17.424 ms/op
     p(99.9990) =     17.433 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.518 ±(99.9%) 0.392 ms/op
Iteration   1: 8.025 ±(99.9%) 0.131 ms/op
                 listUser·p0.00:   2.437 ms/op
                 listUser·p0.50:   7.512 ms/op
                 listUser·p0.90:   10.846 ms/op
                 listUser·p0.95:   12.599 ms/op
                 listUser·p0.99:   17.994 ms/op
                 listUser·p0.999:  19.530 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3986
  mean =      8.025 ±(99.9%) 0.131 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1 
    [ 2.500,  3.750) = 29 
    [ 3.750,  5.000) = 194 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 1163 
    [ 7.500,  8.750) = 851 
    [ 8.750, 10.000) = 504 
    [10.000, 11.250) = 333 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 40 

  Percentiles, ms/op:
      p(0.0000) =      2.437 ms/op
     p(50.0000) =      7.512 ms/op
     p(90.0000) =     10.846 ms/op
     p(95.0000) =     12.599 ms/op
     p(99.0000) =     17.994 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.915          ops/ms
Client.existUser                       thrpt         12.374          ops/ms
Client.getUser                         thrpt         10.267          ops/ms
Client.listUser                        thrpt          3.665          ops/ms
Client.createUser                       avgt          3.057           ms/op
Client.existUser                        avgt          2.063           ms/op
Client.getUser                          avgt          3.095           ms/op
Client.listUser                         avgt          8.332           ms/op
Client.createUser                     sample   9822   3.302 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.296           ms/op
Client.createUser:createUser·p0.50    sample          3.105           ms/op
Client.createUser:createUser·p0.90    sample          4.108           ms/op
Client.createUser:createUser·p0.95    sample          4.489           ms/op
Client.createUser:createUser·p0.99    sample          7.938           ms/op
Client.createUser:createUser·p0.999   sample         16.908           ms/op
Client.createUser:createUser·p0.9999  sample         17.236           ms/op
Client.createUser:createUser·p1.00    sample         17.236           ms/op
Client.existUser                      sample  17761   1.806 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.536           ms/op
Client.existUser:existUser·p0.50      sample          1.669           ms/op
Client.existUser:existUser·p0.90      sample          2.236           ms/op
Client.existUser:existUser·p0.95      sample          2.499           ms/op
Client.existUser:existUser·p0.99      sample          3.543           ms/op
Client.existUser:existUser·p0.999     sample         22.527           ms/op
Client.existUser:existUser·p0.9999    sample         23.666           ms/op
Client.existUser:existUser·p1.00      sample         23.691           ms/op
Client.getUser                        sample  10690   2.992 ± 0.040   ms/op
Client.getUser:getUser·p0.00          sample          0.732           ms/op
Client.getUser:getUser·p0.50          sample          2.826           ms/op
Client.getUser:getUser·p0.90          sample          3.813           ms/op
Client.getUser:getUser·p0.95          sample          4.129           ms/op
Client.getUser:getUser·p0.99          sample          6.670           ms/op
Client.getUser:getUser·p0.999         sample         16.861           ms/op
Client.getUser:getUser·p0.9999        sample         17.424           ms/op
Client.getUser:getUser·p1.00          sample         17.433           ms/op
Client.listUser                       sample   3986   8.025 ± 0.131   ms/op
Client.listUser:listUser·p0.00        sample          2.437           ms/op
Client.listUser:listUser·p0.50        sample          7.512           ms/op
Client.listUser:listUser·p0.90        sample         10.846           ms/op
Client.listUser:listUser·p0.95        sample         12.599           ms/op
Client.listUser:listUser·p0.99        sample         17.994           ms/op
Client.listUser:listUser·p0.999       sample         19.530           ms/op
Client.listUser:listUser·p0.9999      sample         19.857           ms/op
Client.listUser:listUser·p1.00        sample         19.857           ms/op
