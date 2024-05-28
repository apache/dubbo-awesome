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
# Warmup Iteration   1: 1.301 ops/ms
Iteration   1: 5.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.920 ops/ms


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
# Warmup Iteration   1: 5.976 ops/ms
Iteration   1: 11.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.951 ops/ms


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
# Warmup Iteration   1: 5.774 ops/ms
Iteration   1: 11.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.806 ops/ms


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
# Warmup Iteration   1: 4.143 ops/ms
Iteration   1: 7.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.941 ops/ms


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
# Warmup Iteration   1: 4.493 ±(99.9%) 0.088 ms/op
Iteration   1: 2.148 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.148 ms/op


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
# Warmup Iteration   1: 3.436 ±(99.9%) 0.062 ms/op
Iteration   1: 2.052 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.052 ms/op


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
# Warmup Iteration   1: 3.314 ±(99.9%) 0.055 ms/op
Iteration   1: 1.820 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.820 ms/op


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.125 ms/op
Iteration   1: 3.316 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.316 ms/op


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
# Warmup Iteration   1: 3.422 ±(99.9%) 0.091 ms/op
Iteration   1: 2.092 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.659 ms/op
                 createUser·p0.50:   1.823 ms/op
                 createUser·p0.90:   2.687 ms/op
                 createUser·p0.95:   2.953 ms/op
                 createUser·p0.99:   6.768 ms/op
                 createUser·p0.999:  31.153 ms/op
                 createUser·p0.9999: 32.537 ms/op
                 createUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15292
  mean =      2.092 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13120 
    [ 2.500,  5.000) = 1907 
    [ 5.000,  7.500) = 168 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.953 ms/op
     p(99.0000) =      6.768 ms/op
     p(99.9000) =     31.153 ms/op
     p(99.9900) =     32.537 ms/op
     p(99.9990) =     32.866 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.074 ms/op
Iteration   1: 1.759 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.775 ms/op
                 existUser·p0.50:   1.663 ms/op
                 existUser·p0.90:   2.029 ms/op
                 existUser·p0.95:   2.224 ms/op
                 existUser·p0.99:   3.296 ms/op
                 existUser·p0.999:  14.959 ms/op
                 existUser·p0.9999: 15.158 ms/op
                 existUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18460
  mean =      1.759 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 146 
    [ 1.250,  2.500) = 17846 
    [ 2.500,  3.750) = 329 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      1.663 ms/op
     p(90.0000) =      2.029 ms/op
     p(95.0000) =      2.224 ms/op
     p(99.0000) =      3.296 ms/op
     p(99.9000) =     14.959 ms/op
     p(99.9900) =     15.158 ms/op
     p(99.9990) =     15.172 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.089 ms/op
Iteration   1: 1.986 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.466 ms/op
                 getUser·p0.50:   1.835 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.736 ms/op
                 getUser·p0.99:   3.841 ms/op
                 getUser·p0.999:  13.713 ms/op
                 getUser·p0.9999: 14.301 ms/op
                 getUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16115
  mean =      1.986 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 275 
    [ 1.250,  2.500) = 14135 
    [ 2.500,  3.750) = 1500 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      3.841 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     14.301 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 4.945 ±(99.9%) 0.156 ms/op
Iteration   1: 3.396 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.378 ms/op
                 listUser·p0.50:   3.207 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.708 ms/op
                 listUser·p0.999:  12.599 ms/op
                 listUser·p0.9999: 13.386 ms/op
                 listUser·p1.00:   13.386 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9418
  mean =      3.396 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 475 
    [ 2.500,  3.750) = 6493 
    [ 3.750,  5.000) = 2116 
    [ 5.000,  6.250) = 190 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.708 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     13.386 ms/op
     p(99.9990) =     13.386 ms/op
     p(99.9999) =     13.386 ms/op
    p(100.0000) =     13.386 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.920          ops/ms
ClientSimple.existUser                       thrpt         11.951          ops/ms
ClientSimple.getUser                         thrpt         11.806          ops/ms
ClientSimple.listUser                        thrpt          7.941          ops/ms
ClientSimple.createUser                       avgt          2.148           ms/op
ClientSimple.existUser                        avgt          2.052           ms/op
ClientSimple.getUser                          avgt          1.820           ms/op
ClientSimple.listUser                         avgt          3.316           ms/op
ClientSimple.createUser                     sample  15292   2.092 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.659           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.823           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.768           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.153           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.537           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.866           ms/op
ClientSimple.existUser                      sample  18460   1.759 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.775           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.663           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.029           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.296           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.959           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.158           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.172           ms/op
ClientSimple.getUser                        sample  16115   1.986 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.466           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.835           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.841           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.713           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.301           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.402           ms/op
ClientSimple.listUser                       sample   9418   3.396 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.378           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.207           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.708           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.599           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.386           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.386           ms/op

Benchmark result is saved to 1716897995881.json
