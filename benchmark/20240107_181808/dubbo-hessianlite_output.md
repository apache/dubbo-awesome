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
# Warmup Iteration   1: 2.617 ops/ms
Iteration   1: 5.696 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.696 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.317 ops/ms
Iteration   1: 11.684 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.684 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.270 ops/ms
Iteration   1: 8.695 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.695 ops/ms


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
# Warmup Iteration   1: 1.901 ops/ms
Iteration   1: 3.726 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.726 ops/ms


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
# Warmup Iteration   1: 5.117 ±(99.9%) 0.064 ms/op
Iteration   1: 3.355 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.355 ms/op


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
# Warmup Iteration   1: 3.137 ±(99.9%) 0.037 ms/op
Iteration   1: 1.916 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.916 ms/op


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.065 ms/op
Iteration   1: 2.722 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.722 ms/op


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
# Warmup Iteration   1: 12.412 ±(99.9%) 0.215 ms/op
Iteration   1: 8.625 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.625 ms/op


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
# Warmup Iteration   1: 4.793 ±(99.9%) 0.120 ms/op
Iteration   1: 3.492 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.855 ms/op
                 createUser·p0.99:   8.094 ms/op
                 createUser·p0.999:  11.212 ms/op
                 createUser·p0.9999: 14.729 ms/op
                 createUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9386
  mean =      3.492 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 895 
    [ 2.500,  3.750) = 5501 
    [ 3.750,  5.000) = 2608 
    [ 5.000,  6.250) = 238 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.855 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     11.212 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     14.729 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 3.140 ±(99.9%) 0.066 ms/op
Iteration   1: 1.972 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   1.892 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.527 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  27.230 ms/op
                 existUser·p0.9999: 27.670 ms/op
                 existUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16450
  mean =      1.972 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15519 
    [ 2.500,  5.000) = 876 
    [ 5.000,  7.500) = 22 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.527 ms/op
     p(99.0000) =      3.514 ms/op
     p(99.9000) =     27.230 ms/op
     p(99.9900) =     27.670 ms/op
     p(99.9990) =     27.754 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 5.270 ±(99.9%) 0.135 ms/op
Iteration   1: 2.953 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   2.859 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   4.054 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  7.958 ms/op
                 getUser·p0.9999: 9.808 ms/op
                 getUser·p1.00:   9.863 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10845
  mean =      2.953 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 13 
    [ 1.500,  2.000) = 157 
    [ 2.000,  2.500) = 2616 
    [ 2.500,  3.000) = 3565 
    [ 3.000,  3.500) = 2962 
    [ 3.500,  4.000) = 956 
    [ 4.000,  4.500) = 283 
    [ 4.500,  5.000) = 109 
    [ 5.000,  5.500) = 92 
    [ 5.500,  6.000) = 46 
    [ 6.000,  6.500) = 10 
    [ 6.500,  7.000) = 1 
    [ 7.000,  7.500) = 3 
    [ 7.500,  8.000) = 25 
    [ 8.000,  8.500) = 3 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.054 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =      7.958 ms/op
     p(99.9900) =      9.808 ms/op
     p(99.9990) =      9.863 ms/op
     p(99.9999) =      9.863 ms/op
    p(100.0000) =      9.863 ms/op


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
# Warmup Iteration   1: 11.716 ±(99.9%) 0.371 ms/op
Iteration   1: 7.980 ±(99.9%) 0.091 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   7.864 ms/op
                 listUser·p0.90:   10.224 ms/op
                 listUser·p0.95:   10.977 ms/op
                 listUser·p0.99:   12.762 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4006
  mean =      7.980 ±(99.9%) 0.091 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1 
    [ 2.500,  3.750) = 13 
    [ 3.750,  5.000) = 97 
    [ 5.000,  6.250) = 485 
    [ 6.250,  7.500) = 1035 
    [ 7.500,  8.750) = 1220 
    [ 8.750, 10.000) = 681 
    [10.000, 11.250) = 312 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.269 ms/op
     p(50.0000) =      7.864 ms/op
     p(90.0000) =     10.224 ms/op
     p(95.0000) =     10.977 ms/op
     p(99.0000) =     12.762 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.696          ops/ms
Client.existUser                       thrpt         11.684          ops/ms
Client.getUser                         thrpt          8.695          ops/ms
Client.listUser                        thrpt          3.726          ops/ms
Client.createUser                       avgt          3.355           ms/op
Client.existUser                        avgt          1.916           ms/op
Client.getUser                          avgt          2.722           ms/op
Client.listUser                         avgt          8.625           ms/op
Client.createUser                     sample   9386   3.492 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          1.247           ms/op
Client.createUser:createUser·p0.50    sample          3.400           ms/op
Client.createUser:createUser·p0.90    sample          4.391           ms/op
Client.createUser:createUser·p0.95    sample          4.855           ms/op
Client.createUser:createUser·p0.99    sample          8.094           ms/op
Client.createUser:createUser·p0.999   sample         11.212           ms/op
Client.createUser:createUser·p0.9999  sample         14.729           ms/op
Client.createUser:createUser·p1.00    sample         14.729           ms/op
Client.existUser                      sample  16450   1.972 ± 0.031   ms/op
Client.existUser:existUser·p0.00      sample          0.522           ms/op
Client.existUser:existUser·p0.50      sample          1.892           ms/op
Client.existUser:existUser·p0.90      sample          2.347           ms/op
Client.existUser:existUser·p0.95      sample          2.527           ms/op
Client.existUser:existUser·p0.99      sample          3.514           ms/op
Client.existUser:existUser·p0.999     sample         27.230           ms/op
Client.existUser:existUser·p0.9999    sample         27.670           ms/op
Client.existUser:existUser·p1.00      sample         27.754           ms/op
Client.getUser                        sample  10845   2.953 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          1.204           ms/op
Client.getUser:getUser·p0.50          sample          2.859           ms/op
Client.getUser:getUser·p0.90          sample          3.686           ms/op
Client.getUser:getUser·p0.95          sample          4.054           ms/op
Client.getUser:getUser·p0.99          sample          5.382           ms/op
Client.getUser:getUser·p0.999         sample          7.958           ms/op
Client.getUser:getUser·p0.9999        sample          9.808           ms/op
Client.getUser:getUser·p1.00          sample          9.863           ms/op
Client.listUser                       sample   4006   7.980 ± 0.091   ms/op
Client.listUser:listUser·p0.00        sample          2.269           ms/op
Client.listUser:listUser·p0.50        sample          7.864           ms/op
Client.listUser:listUser·p0.90        sample         10.224           ms/op
Client.listUser:listUser·p0.95        sample         10.977           ms/op
Client.listUser:listUser·p0.99        sample         12.762           ms/op
Client.listUser:listUser·p0.999       sample         16.974           ms/op
Client.listUser:listUser·p0.9999      sample         18.055           ms/op
Client.listUser:listUser·p1.00        sample         18.055           ms/op
