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
# Warmup Iteration   1: 1.671 ops/ms
Iteration   1: 6.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.450 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.656 ops/ms
Iteration   1: 12.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.837 ops/ms


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
# Warmup Iteration   1: 5.346 ops/ms
Iteration   1: 12.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.476 ops/ms


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
# Warmup Iteration   1: 4.690 ops/ms
Iteration   1: 8.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.545 ops/ms


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.061 ms/op
Iteration   1: 2.062 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.062 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.133 ±(99.9%) 0.046 ms/op
Iteration   1: 1.974 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.974 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.262 ±(99.9%) 0.066 ms/op
Iteration   1: 2.162 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.162 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.422 ±(99.9%) 0.089 ms/op
Iteration   1: 3.192 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.192 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.325 ±(99.9%) 0.082 ms/op
Iteration   1: 2.294 ±(99.9%) 0.073 ms/op
                 createUser·p0.00:   0.399 ms/op
                 createUser·p0.50:   2.138 ms/op
                 createUser·p0.90:   2.613 ms/op
                 createUser·p0.95:   2.798 ms/op
                 createUser·p0.99:   7.205 ms/op
                 createUser·p0.999:  49.459 ms/op
                 createUser·p0.9999: 54.395 ms/op
                 createUser·p1.00:   54.395 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13982
  mean =      2.294 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13819 
    [ 5.000, 10.000) = 67 
    [10.000, 15.000) = 30 
    [15.000, 20.000) = 1 
    [20.000, 25.000) = 33 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 19 
    [50.000, 55.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      2.138 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      7.205 ms/op
     p(99.9000) =     49.459 ms/op
     p(99.9900) =     54.395 ms/op
     p(99.9990) =     54.395 ms/op
     p(99.9999) =     54.395 ms/op
    p(100.0000) =     54.395 ms/op


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
# Warmup Iteration   1: 2.833 ±(99.9%) 0.067 ms/op
Iteration   1: 1.936 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.297 ms/op
                 existUser·p0.50:   1.866 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   3.489 ms/op
                 existUser·p0.999:  10.404 ms/op
                 existUser·p0.9999: 10.585 ms/op
                 existUser·p1.00:   10.617 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16509
  mean =      1.936 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 670 
    [ 1.250,  2.500) = 14788 
    [ 2.500,  3.750) = 903 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.297 ms/op
     p(50.0000) =      1.866 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.489 ms/op
     p(99.9000) =     10.404 ms/op
     p(99.9900) =     10.585 ms/op
     p(99.9990) =     10.617 ms/op
     p(99.9999) =     10.617 ms/op
    p(100.0000) =     10.617 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.082 ms/op
Iteration   1: 2.056 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.582 ms/op
                 getUser·p0.50:   1.964 ms/op
                 getUser·p0.90:   2.613 ms/op
                 getUser·p0.95:   2.855 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  15.745 ms/op
                 getUser·p0.9999: 15.834 ms/op
                 getUser·p1.00:   15.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15600
  mean =      2.056 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 381 
    [ 1.250,  2.500) = 13067 
    [ 2.500,  3.750) = 1993 
    [ 3.750,  5.000) = 32 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     15.834 ms/op
     p(99.9990) =     15.843 ms/op
     p(99.9999) =     15.843 ms/op
    p(100.0000) =     15.843 ms/op


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.108 ms/op
Iteration   1: 3.169 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.030 ms/op
                 listUser·p0.99:   4.956 ms/op
                 listUser·p0.999:  32.440 ms/op
                 listUser·p0.9999: 32.538 ms/op
                 listUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10094
  mean =      3.169 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1401 
    [ 2.500,  5.000) = 8605 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =     32.440 ms/op
     p(99.9900) =     32.538 ms/op
     p(99.9990) =     32.539 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.450          ops/ms
ClientSimple.existUser                       thrpt         12.837          ops/ms
ClientSimple.getUser                         thrpt         12.476          ops/ms
ClientSimple.listUser                        thrpt          8.545          ops/ms
ClientSimple.createUser                       avgt          2.062           ms/op
ClientSimple.existUser                        avgt          1.974           ms/op
ClientSimple.getUser                          avgt          2.162           ms/op
ClientSimple.listUser                         avgt          3.192           ms/op
ClientSimple.createUser                     sample  13982   2.294 ± 0.073   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.399           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.138           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.205           ms/op
ClientSimple.createUser:createUser·p0.999   sample         49.459           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         54.395           ms/op
ClientSimple.createUser:createUser·p1.00    sample         54.395           ms/op
ClientSimple.existUser                      sample  16509   1.936 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.297           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.866           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.489           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.404           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.585           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.617           ms/op
ClientSimple.getUser                        sample  15600   2.056 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.582           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.964           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.613           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.764           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.745           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.834           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.843           ms/op
ClientSimple.listUser                       sample  10094   3.169 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.041           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.953           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.842           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.030           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.956           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.440           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         32.538           ms/op
ClientSimple.listUser:listUser·p1.00        sample         32.539           ms/op

Benchmark result is saved to 1716314698168.json
