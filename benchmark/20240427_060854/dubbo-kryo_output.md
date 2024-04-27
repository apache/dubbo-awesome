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
# Warmup Iteration   1: 1.612 ops/ms
Iteration   1: 7.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.122 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.139 ops/ms
Iteration   1: 13.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.154 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.331 ops/ms
Iteration   1: 12.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.464 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.543 ops/ms
Iteration   1: 7.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.806 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.762 ±(99.9%) 0.109 ms/op
Iteration   1: 2.276 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.276 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.613 ±(99.9%) 0.080 ms/op
Iteration   1: 1.881 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.881 ms/op


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
# Warmup Iteration   1: 3.695 ±(99.9%) 0.059 ms/op
Iteration   1: 2.007 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.007 ms/op


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
# Warmup Iteration   1: 4.815 ±(99.9%) 0.106 ms/op
Iteration   1: 3.407 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.407 ms/op


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
# Warmup Iteration   1: 3.559 ±(99.9%) 0.090 ms/op
Iteration   1: 2.470 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.359 ms/op
                 createUser·p0.99:   9.836 ms/op
                 createUser·p0.999:  19.370 ms/op
                 createUser·p0.9999: 19.927 ms/op
                 createUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12937
  mean =      2.470 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 9261 
    [ 2.500,  3.750) = 3206 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.359 ms/op
     p(99.0000) =      9.836 ms/op
     p(99.9000) =     19.370 ms/op
     p(99.9900) =     19.927 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.078 ms/op
Iteration   1: 1.969 ±(99.9%) 0.041 ms/op
                 existUser·p0.00:   0.595 ms/op
                 existUser·p0.50:   1.690 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.826 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  32.248 ms/op
                 existUser·p0.9999: 33.010 ms/op
                 existUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16286
  mean =      1.969 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14342 
    [ 2.500,  5.000) = 1824 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      1.690 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =     32.248 ms/op
     p(99.9900) =     33.010 ms/op
     p(99.9990) =     33.030 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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
# Warmup Iteration   1: 3.615 ±(99.9%) 0.099 ms/op
Iteration   1: 1.996 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   1.894 ms/op
                 getUser·p0.90:   2.438 ms/op
                 getUser·p0.95:   2.798 ms/op
                 getUser·p0.99:   3.888 ms/op
                 getUser·p0.999:  13.418 ms/op
                 getUser·p0.9999: 13.763 ms/op
                 getUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16096
  mean =      1.996 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 14543 
    [ 2.500,  3.750) = 1231 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      1.894 ms/op
     p(90.0000) =      2.438 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.888 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     13.763 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 5.014 ±(99.9%) 0.142 ms/op
Iteration   1: 3.586 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  20.315 ms/op
                 listUser·p0.9999: 21.856 ms/op
                 listUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8910
  mean =      3.586 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 525 
    [ 2.500,  5.000) = 7993 
    [ 5.000,  7.500) = 351 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     20.315 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.122          ops/ms
ClientSimple.existUser                       thrpt         13.154          ops/ms
ClientSimple.getUser                         thrpt         12.464          ops/ms
ClientSimple.listUser                        thrpt          7.806          ops/ms
ClientSimple.createUser                       avgt          2.276           ms/op
ClientSimple.existUser                        avgt          1.881           ms/op
ClientSimple.getUser                          avgt          2.007           ms/op
ClientSimple.listUser                         avgt          3.407           ms/op
ClientSimple.createUser                     sample  12937   2.470 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.687           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.990           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.359           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.836           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.370           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.927           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.956           ms/op
ClientSimple.existUser                      sample  16286   1.969 ± 0.041   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.595           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.690           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.826           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.456           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.248           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         33.010           ms/op
ClientSimple.existUser:existUser·p1.00      sample         33.030           ms/op
ClientSimple.getUser                        sample  16096   1.996 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.629           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.894           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.438           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.888           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.418           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.763           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.763           ms/op
ClientSimple.listUser                       sample   8910   3.586 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.029           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.850           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.726           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.315           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.856           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.856           ms/op

Benchmark result is saved to 1714197883865.json
