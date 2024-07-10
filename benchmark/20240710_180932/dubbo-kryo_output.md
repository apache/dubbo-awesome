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
# Warmup Iteration   1: 1.689 ops/ms
Iteration   1: 7.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.272 ops/ms


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
# Warmup Iteration   1: 6.672 ops/ms
Iteration   1: 13.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.245 ops/ms


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
# Warmup Iteration   1: 5.395 ops/ms
Iteration   1: 13.359 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.359 ops/ms


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
# Warmup Iteration   1: 5.802 ops/ms
Iteration   1: 8.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.750 ops/ms


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
# Warmup Iteration   1: 4.204 ±(99.9%) 0.092 ms/op
Iteration   1: 2.168 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.168 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.050 ms/op
Iteration   1: 1.855 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.855 ms/op


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
# Warmup Iteration   1: 3.154 ±(99.9%) 0.048 ms/op
Iteration   1: 1.952 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.952 ms/op


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
# Warmup Iteration   1: 3.963 ±(99.9%) 0.069 ms/op
Iteration   1: 3.154 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.154 ms/op


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
# Warmup Iteration   1: 3.531 ±(99.9%) 0.089 ms/op
Iteration   1: 2.016 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   1.849 ms/op
                 createUser·p0.90:   2.609 ms/op
                 createUser·p0.95:   2.929 ms/op
                 createUser·p0.99:   4.307 ms/op
                 createUser·p0.999:  14.254 ms/op
                 createUser·p0.9999: 15.178 ms/op
                 createUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15863
  mean =      2.016 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 131 
    [ 1.250,  2.500) = 13741 
    [ 2.500,  3.750) = 1733 
    [ 3.750,  5.000) = 153 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      4.307 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     15.178 ms/op
     p(99.9990) =     15.188 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.255 ±(99.9%) 0.104 ms/op
Iteration   1: 1.784 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.658 ms/op
                 existUser·p0.50:   1.675 ms/op
                 existUser·p0.90:   2.130 ms/op
                 existUser·p0.95:   2.298 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  13.861 ms/op
                 existUser·p0.9999: 14.144 ms/op
                 existUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17909
  mean =      1.784 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 384 
    [ 1.250,  2.500) = 17102 
    [ 2.500,  3.750) = 229 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      1.675 ms/op
     p(90.0000) =      2.130 ms/op
     p(95.0000) =      2.298 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     14.144 ms/op
     p(99.9990) =     14.221 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.248 ±(99.9%) 0.076 ms/op
Iteration   1: 1.964 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.379 ms/op
                 getUser·p0.50:   1.872 ms/op
                 getUser·p0.90:   2.322 ms/op
                 getUser·p0.95:   2.519 ms/op
                 getUser·p0.99:   4.039 ms/op
                 getUser·p0.999:  20.601 ms/op
                 getUser·p0.9999: 21.725 ms/op
                 getUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16308
  mean =      1.964 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15427 
    [ 2.500,  5.000) = 798 
    [ 5.000,  7.500) = 11 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      4.039 ms/op
     p(99.9000) =     20.601 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 4.413 ±(99.9%) 0.124 ms/op
Iteration   1: 3.149 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.269 ms/op
                 listUser·p0.99:   5.104 ms/op
                 listUser·p0.999:  14.266 ms/op
                 listUser·p0.9999: 14.623 ms/op
                 listUser·p1.00:   14.631 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10297
  mean =      3.149 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 567 
    [ 2.500,  3.750) = 7912 
    [ 3.750,  5.000) = 1689 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.269 ms/op
     p(99.0000) =      5.104 ms/op
     p(99.9000) =     14.266 ms/op
     p(99.9900) =     14.623 ms/op
     p(99.9990) =     14.631 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.272          ops/ms
ClientSimple.existUser                       thrpt         13.245          ops/ms
ClientSimple.getUser                         thrpt         13.359          ops/ms
ClientSimple.listUser                        thrpt          8.750          ops/ms
ClientSimple.createUser                       avgt          2.168           ms/op
ClientSimple.existUser                        avgt          1.855           ms/op
ClientSimple.getUser                          avgt          1.952           ms/op
ClientSimple.listUser                         avgt          3.154           ms/op
ClientSimple.createUser                     sample  15863   2.016 ± 0.021   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.744           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.849           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.609           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.307           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.254           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.178           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.188           ms/op
ClientSimple.existUser                      sample  17909   1.784 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.658           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.675           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.760           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.861           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.144           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.221           ms/op
ClientSimple.getUser                        sample  16308   1.964 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.379           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.872           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.322           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.039           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.601           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.725           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.725           ms/op
ClientSimple.listUser                       sample  10297   3.149 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.196           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.888           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.026           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.269           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.104           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.266           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.623           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.631           ms/op

Benchmark result is saved to 1720634720807.json
