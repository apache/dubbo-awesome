# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.968 ops/ms
Iteration   1: 7.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.071 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.948 ops/ms
Iteration   1: 13.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.095 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.051 ops/ms
Iteration   1: 11.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.704 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.002 ops/ms
Iteration   1: 7.693 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.693 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.074 ms/op
Iteration   1: 1.959 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.959 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.004 ±(99.9%) 0.042 ms/op
Iteration   1: 1.790 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.790 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.322 ±(99.9%) 0.054 ms/op
Iteration   1: 1.783 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.783 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.289 ±(99.9%) 0.085 ms/op
Iteration   1: 2.941 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.941 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.653 ±(99.9%) 0.101 ms/op
Iteration   1: 2.100 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   1.886 ms/op
                 createUser·p0.90:   2.417 ms/op
                 createUser·p0.95:   2.679 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  29.025 ms/op
                 createUser·p0.9999: 31.752 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15214
  mean =      2.100 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14058 
    [ 2.500,  5.000) = 947 
    [ 5.000,  7.500) = 23 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     29.025 ms/op
     p(99.9900) =     31.752 ms/op
     p(99.9990) =     31.752 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.950 ±(99.9%) 0.065 ms/op
Iteration   1: 1.749 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   1.645 ms/op
                 existUser·p0.90:   2.150 ms/op
                 existUser·p0.95:   2.294 ms/op
                 existUser·p0.99:   3.086 ms/op
                 existUser·p0.999:  13.861 ms/op
                 existUser·p0.9999: 14.293 ms/op
                 existUser·p1.00:   14.320 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18264
  mean =      1.749 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 397 
    [ 1.250,  2.500) = 17407 
    [ 2.500,  3.750) = 369 
    [ 3.750,  5.000) = 51 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      1.645 ms/op
     p(90.0000) =      2.150 ms/op
     p(95.0000) =      2.294 ms/op
     p(99.0000) =      3.086 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     14.293 ms/op
     p(99.9990) =     14.320 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.082 ±(99.9%) 0.080 ms/op
Iteration   1: 2.100 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.488 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.429 ms/op
                 getUser·p0.95:   2.638 ms/op
                 getUser·p0.99:   3.271 ms/op
                 getUser·p0.999:  28.714 ms/op
                 getUser·p0.9999: 29.513 ms/op
                 getUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15238
  mean =      2.100 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14059 
    [ 2.500,  5.000) = 1100 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.488 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.271 ms/op
     p(99.9000) =     28.714 ms/op
     p(99.9900) =     29.513 ms/op
     p(99.9990) =     29.753 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.441 ±(99.9%) 0.117 ms/op
Iteration   1: 3.152 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  15.731 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9997
  mean =      3.152 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1058 
    [ 2.500,  5.000) = 8736 
    [ 5.000,  7.500) = 154 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     15.731 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.071          ops/ms
ClientSimple.existUser                       thrpt         13.095          ops/ms
ClientSimple.getUser                         thrpt         11.704          ops/ms
ClientSimple.listUser                        thrpt          7.693          ops/ms
ClientSimple.createUser                       avgt          1.959           ms/op
ClientSimple.existUser                        avgt          1.790           ms/op
ClientSimple.getUser                          avgt          1.783           ms/op
ClientSimple.listUser                         avgt          2.941           ms/op
ClientSimple.createUser                     sample  15214   2.100 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.669           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.886           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.417           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.962           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.025           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.752           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.752           ms/op
ClientSimple.existUser                      sample  18264   1.749 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.637           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.645           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.150           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.086           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.861           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.293           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.320           ms/op
ClientSimple.getUser                        sample  15238   2.100 ± 0.038   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.488           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.429           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.271           ms/op
ClientSimple.getUser:getUser·p0.999         sample         28.714           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.513           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.753           ms/op
ClientSimple.listUser                       sample   9997   3.152 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.143           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.961           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.108           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.800           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.731           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.019           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.019           ms/op

Benchmark result is saved to 1712340326014.json
