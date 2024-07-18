# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.771 ops/ms
Iteration   1: 7.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.693 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.419 ops/ms
Iteration   1: 12.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.853 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.720 ops/ms
Iteration   1: 13.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.217 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.231 ops/ms
Iteration   1: 8.562 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.562 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.078 ms/op
Iteration   1: 2.242 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.242 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.209 ±(99.9%) 0.050 ms/op
Iteration   1: 1.889 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.889 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.216 ±(99.9%) 0.053 ms/op
Iteration   1: 2.250 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.250 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.128 ±(99.9%) 0.096 ms/op
Iteration   1: 3.770 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.770 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.686 ±(99.9%) 0.106 ms/op
Iteration   1: 2.487 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.269 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.363 ms/op
                 createUser·p0.99:   5.738 ms/op
                 createUser·p0.999:  28.082 ms/op
                 createUser·p0.9999: 29.107 ms/op
                 createUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12852
  mean =      2.487 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9161 
    [ 2.500,  5.000) = 3539 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.363 ms/op
     p(99.0000) =      5.738 ms/op
     p(99.9000) =     28.082 ms/op
     p(99.9900) =     29.107 ms/op
     p(99.9990) =     29.164 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.007 ±(99.9%) 0.066 ms/op
Iteration   1: 1.700 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   1.624 ms/op
                 existUser·p0.90:   2.021 ms/op
                 existUser·p0.95:   2.171 ms/op
                 existUser·p0.99:   2.523 ms/op
                 existUser·p0.999:  13.599 ms/op
                 existUser·p0.9999: 14.276 ms/op
                 existUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18872
  mean =      1.700 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 268 
    [ 1.250,  2.500) = 18402 
    [ 2.500,  3.750) = 129 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      1.624 ms/op
     p(90.0000) =      2.021 ms/op
     p(95.0000) =      2.171 ms/op
     p(99.0000) =      2.523 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     14.276 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.409 ±(99.9%) 0.079 ms/op
Iteration   1: 1.929 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   1.792 ms/op
                 getUser·p0.90:   2.384 ms/op
                 getUser·p0.95:   2.662 ms/op
                 getUser·p0.99:   3.917 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 10.404 ms/op
                 getUser·p1.00:   10.568 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16669
  mean =      1.929 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 16 
    [ 1.000,  2.000) = 11428 
    [ 2.000,  3.000) = 4827 
    [ 3.000,  4.000) = 237 
    [ 4.000,  5.000) = 61 
    [ 5.000,  6.000) = 23 
    [ 6.000,  7.000) = 41 
    [ 7.000,  8.000) = 4 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      3.917 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     10.404 ms/op
     p(99.9990) =     10.568 ms/op
     p(99.9999) =     10.568 ms/op
    p(100.0000) =     10.568 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.231 ±(99.9%) 0.123 ms/op
Iteration   1: 3.387 ±(99.9%) 0.055 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.400 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.515 ms/op
                 listUser·p0.999:  28.429 ms/op
                 listUser·p0.9999: 29.590 ms/op
                 listUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9472
  mean =      3.387 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1315 
    [ 2.500,  5.000) = 7983 
    [ 5.000,  7.500) = 137 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.151 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.515 ms/op
     p(99.9000) =     28.429 ms/op
     p(99.9900) =     29.590 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.693          ops/ms
ClientSimple.existUser                       thrpt         12.853          ops/ms
ClientSimple.getUser                         thrpt         13.217          ops/ms
ClientSimple.listUser                        thrpt          8.562          ops/ms
ClientSimple.createUser                       avgt          2.242           ms/op
ClientSimple.existUser                        avgt          1.889           ms/op
ClientSimple.getUser                          avgt          2.250           ms/op
ClientSimple.listUser                         avgt          3.770           ms/op
ClientSimple.createUser                     sample  12852   2.487 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.063           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.269           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.998           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.363           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.738           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.082           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.107           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.164           ms/op
ClientSimple.existUser                      sample  18872   1.700 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.440           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.624           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.021           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.171           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.599           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.276           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.451           ms/op
ClientSimple.getUser                        sample  16669   1.929 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.727           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.792           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.384           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.662           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.917           ms/op
ClientSimple.getUser:getUser·p0.999         sample          9.437           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.404           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.568           ms/op
ClientSimple.listUser                       sample   9472   3.387 ± 0.055   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.151           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.400           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.067           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.515           ms/op
ClientSimple.listUser:listUser·p0.999       sample         28.429           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.590           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.590           ms/op

Benchmark result is saved to 1721261799500.json
