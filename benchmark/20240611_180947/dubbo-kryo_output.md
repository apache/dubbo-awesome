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
# Warmup Iteration   1: 2.055 ops/ms
Iteration   1: 7.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.003 ops/ms


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
# Warmup Iteration   1: 6.583 ops/ms
Iteration   1: 11.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.914 ops/ms


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
# Warmup Iteration   1: 5.485 ops/ms
Iteration   1: 14.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.162 ops/ms


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
# Warmup Iteration   1: 4.680 ops/ms
Iteration   1: 7.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.680 ops/ms


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.072 ms/op
Iteration   1: 2.209 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.209 ms/op


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.060 ms/op
Iteration   1: 1.668 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.668 ms/op


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
# Warmup Iteration   1: 3.520 ±(99.9%) 0.071 ms/op
Iteration   1: 2.163 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.163 ms/op


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
# Warmup Iteration   1: 4.691 ±(99.9%) 0.090 ms/op
Iteration   1: 3.244 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.244 ms/op


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.098 ms/op
Iteration   1: 1.879 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.373 ms/op
                 createUser·p0.50:   1.745 ms/op
                 createUser·p0.90:   2.179 ms/op
                 createUser·p0.95:   2.377 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  20.019 ms/op
                 createUser·p0.9999: 22.957 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 17131
  mean =      1.879 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16489 
    [ 2.500,  5.000) = 476 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.179 ms/op
     p(95.0000) =      2.377 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =     20.019 ms/op
     p(99.9900) =     22.957 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 3.166 ±(99.9%) 0.073 ms/op
Iteration   1: 2.008 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   1.858 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.617 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  28.180 ms/op
                 existUser·p0.9999: 28.771 ms/op
                 existUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15946
  mean =      2.008 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14809 
    [ 2.500,  5.000) = 1004 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      1.858 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =     28.180 ms/op
     p(99.9900) =     28.771 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.098 ms/op
Iteration   1: 2.160 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.528 ms/op
                 getUser·p0.50:   2.075 ms/op
                 getUser·p0.90:   2.732 ms/op
                 getUser·p0.95:   2.970 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  13.192 ms/op
                 getUser·p0.9999: 13.312 ms/op
                 getUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14797
  mean =      2.160 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 11766 
    [ 2.500,  3.750) = 2646 
    [ 3.750,  5.000) = 137 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.970 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     13.192 ms/op
     p(99.9900) =     13.312 ms/op
     p(99.9990) =     13.320 ms/op
     p(99.9999) =     13.320 ms/op
    p(100.0000) =     13.320 ms/op


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.149 ms/op
Iteration   1: 3.505 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   3.412 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.599 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9121
  mean =      3.505 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 975 
    [ 2.500,  3.750) = 4974 
    [ 3.750,  5.000) = 2771 
    [ 5.000,  6.250) = 142 
    [ 6.250,  7.500) = 156 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.599 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.003          ops/ms
ClientSimple.existUser                       thrpt         11.914          ops/ms
ClientSimple.getUser                         thrpt         14.162          ops/ms
ClientSimple.listUser                        thrpt          7.680          ops/ms
ClientSimple.createUser                       avgt          2.209           ms/op
ClientSimple.existUser                        avgt          1.668           ms/op
ClientSimple.getUser                          avgt          2.163           ms/op
ClientSimple.listUser                         avgt          3.244           ms/op
ClientSimple.createUser                     sample  17131   1.879 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.373           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.745           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.179           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.377           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.932           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.019           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.957           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.673           ms/op
ClientSimple.existUser                      sample  15946   2.008 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.501           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.858           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.874           ms/op
ClientSimple.existUser:existUser·p0.999     sample         28.180           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         28.771           ms/op
ClientSimple.existUser:existUser·p1.00      sample         28.869           ms/op
ClientSimple.getUser                        sample  14797   2.160 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.528           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.075           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.970           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.375           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.192           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.312           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.320           ms/op
ClientSimple.listUser                       sample   9121   3.505 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.030           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.412           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.599           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.203           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.088           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.088           ms/op

Benchmark result is saved to 1718129129312.json
