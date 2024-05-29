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
# Warmup Iteration   1: 1.824 ops/ms
Iteration   1: 6.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.894 ops/ms


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
# Warmup Iteration   1: 6.360 ops/ms
Iteration   1: 13.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.421 ops/ms


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
# Warmup Iteration   1: 5.824 ops/ms
Iteration   1: 13.254 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.254 ops/ms


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
# Warmup Iteration   1: 5.401 ops/ms
Iteration   1: 8.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.667 ops/ms


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.073 ms/op
Iteration   1: 2.101 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.101 ms/op


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
# Warmup Iteration   1: 3.242 ±(99.9%) 0.047 ms/op
Iteration   1: 2.078 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.078 ms/op


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
# Warmup Iteration   1: 3.062 ±(99.9%) 0.063 ms/op
Iteration   1: 1.906 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.906 ms/op


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
# Warmup Iteration   1: 6.012 ±(99.9%) 0.116 ms/op
Iteration   1: 3.544 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.544 ms/op


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
# Warmup Iteration   1: 3.504 ±(99.9%) 0.076 ms/op
Iteration   1: 2.367 ±(99.9%) 0.110 ms/op
                 createUser·p0.00:   0.390 ms/op
                 createUser·p0.50:   2.005 ms/op
                 createUser·p0.90:   2.519 ms/op
                 createUser·p0.95:   2.832 ms/op
                 createUser·p0.99:   11.993 ms/op
                 createUser·p0.999:  84.739 ms/op
                 createUser·p0.9999: 86.809 ms/op
                 createUser·p1.00:   86.901 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13491
  mean =      2.367 ±(99.9%) 0.110 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13153 
    [ 5.000, 10.000) = 186 
    [10.000, 15.000) = 44 
    [15.000, 20.000) = 66 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 3 
    [65.000, 70.000) = 1 
    [70.000, 75.000) = 4 
    [75.000, 80.000) = 1 
    [80.000, 85.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.390 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.832 ms/op
     p(99.0000) =     11.993 ms/op
     p(99.9000) =     84.739 ms/op
     p(99.9900) =     86.809 ms/op
     p(99.9990) =     86.901 ms/op
     p(99.9999) =     86.901 ms/op
    p(100.0000) =     86.901 ms/op


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
# Warmup Iteration   1: 3.285 ±(99.9%) 0.071 ms/op
Iteration   1: 1.822 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   1.679 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   4.068 ms/op
                 existUser·p0.999:  18.888 ms/op
                 existUser·p0.9999: 19.185 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17587
  mean =      1.822 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 446 
    [ 1.250,  2.500) = 16526 
    [ 2.500,  3.750) = 421 
    [ 3.750,  5.000) = 53 
    [ 5.000,  6.250) = 61 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      4.068 ms/op
     p(99.9000) =     18.888 ms/op
     p(99.9900) =     19.185 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 3.007 ±(99.9%) 0.077 ms/op
Iteration   1: 1.889 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.515 ms/op
                 getUser·p0.50:   1.778 ms/op
                 getUser·p0.90:   2.322 ms/op
                 getUser·p0.95:   2.572 ms/op
                 getUser·p0.99:   3.902 ms/op
                 getUser·p0.999:  20.152 ms/op
                 getUser·p0.9999: 20.561 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17247
  mean =      1.889 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16258 
    [ 2.500,  5.000) = 873 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.902 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     20.561 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 4.494 ±(99.9%) 0.119 ms/op
Iteration   1: 3.311 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.351 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   6.021 ms/op
                 listUser·p0.999:  7.377 ms/op
                 listUser·p0.9999: 7.905 ms/op
                 listUser·p1.00:   7.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9646
  mean =      3.311 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 1 
    [1.500, 2.000) = 119 
    [2.000, 2.500) = 2173 
    [2.500, 3.000) = 1585 
    [3.000, 3.500) = 1603 
    [3.500, 4.000) = 2332 
    [4.000, 4.500) = 1207 
    [4.500, 5.000) = 232 
    [5.000, 5.500) = 175 
    [5.500, 6.000) = 114 
    [6.000, 6.500) = 67 
    [6.500, 7.000) = 19 
    [7.000, 7.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =      7.377 ms/op
     p(99.9900) =      7.905 ms/op
     p(99.9990) =      7.905 ms/op
     p(99.9999) =      7.905 ms/op
    p(100.0000) =      7.905 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.894          ops/ms
ClientSimple.existUser                       thrpt         13.421          ops/ms
ClientSimple.getUser                         thrpt         13.254          ops/ms
ClientSimple.listUser                        thrpt          8.667          ops/ms
ClientSimple.createUser                       avgt          2.101           ms/op
ClientSimple.existUser                        avgt          2.078           ms/op
ClientSimple.getUser                          avgt          1.906           ms/op
ClientSimple.listUser                         avgt          3.544           ms/op
ClientSimple.createUser                     sample  13491   2.367 ± 0.110   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.390           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.005           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.519           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.832           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.993           ms/op
ClientSimple.createUser:createUser·p0.999   sample         84.739           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         86.809           ms/op
ClientSimple.createUser:createUser·p1.00    sample         86.901           ms/op
ClientSimple.existUser                      sample  17587   1.822 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.535           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.679           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.068           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.888           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.185           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.235           ms/op
ClientSimple.getUser                        sample  17247   1.889 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.515           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.778           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.322           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.902           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.152           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.561           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.775           ms/op
ClientSimple.listUser                       sample   9646   3.311 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.466           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.351           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.792           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.021           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.377           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.905           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.905           ms/op

Benchmark result is saved to 1716984393454.json
