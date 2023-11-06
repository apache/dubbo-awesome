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
# Warmup Iteration   1: 2.619 ops/ms
Iteration   1: 5.593 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.593 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.030 ops/ms
Iteration   1: 13.283 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.283 ops/ms


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
# Warmup Iteration   1: 4.545 ops/ms
Iteration   1: 9.898 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.898 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.160 ops/ms
Iteration   1: 3.957 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.957 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.926 ±(99.9%) 0.065 ms/op
Iteration   1: 2.976 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.976 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.834 ±(99.9%) 0.045 ms/op
Iteration   1: 1.757 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.757 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.241 ±(99.9%) 0.061 ms/op
Iteration   1: 3.063 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.063 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.499 ±(99.9%) 0.175 ms/op
Iteration   1: 7.224 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.224 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.584 ±(99.9%) 0.087 ms/op
Iteration   1: 2.950 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.716 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   7.900 ms/op
                 createUser·p0.999:  20.939 ms/op
                 createUser·p0.9999: 22.378 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10840
  mean =      2.950 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2266 
    [ 2.500,  5.000) = 8307 
    [ 5.000,  7.500) = 131 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      2.716 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      7.900 ms/op
     p(99.9000) =     20.939 ms/op
     p(99.9900) =     22.378 ms/op
     p(99.9990) =     22.381 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.236 ±(99.9%) 0.071 ms/op
Iteration   1: 1.915 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   1.759 ms/op
                 existUser·p0.90:   2.597 ms/op
                 existUser·p0.95:   2.879 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  6.218 ms/op
                 existUser·p0.9999: 7.181 ms/op
                 existUser·p1.00:   7.307 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16701
  mean =      1.915 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 159 
    [1.000, 1.500) = 3321 
    [1.500, 2.000) = 7078 
    [2.000, 2.500) = 4008 
    [2.500, 3.000) = 1596 
    [3.000, 3.500) = 358 
    [3.500, 4.000) = 57 
    [4.000, 4.500) = 1 
    [4.500, 5.000) = 53 
    [5.000, 5.500) = 31 
    [5.500, 6.000) = 22 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 11 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      6.218 ms/op
     p(99.9900) =      7.181 ms/op
     p(99.9990) =      7.307 ms/op
     p(99.9999) =      7.307 ms/op
    p(100.0000) =      7.307 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.298 ±(99.9%) 0.090 ms/op
Iteration   1: 2.726 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.604 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.401 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   6.170 ms/op
                 getUser·p0.999:  15.270 ms/op
                 getUser·p0.9999: 15.647 ms/op
                 getUser·p1.00:   15.647 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11706
  mean =      2.726 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 5194 
    [ 2.500,  3.750) = 5952 
    [ 3.750,  5.000) = 340 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.604 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.401 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      6.170 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     15.647 ms/op
     p(99.9990) =     15.647 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.068 ±(99.9%) 0.413 ms/op
Iteration   1: 8.707 ±(99.9%) 0.247 ms/op
                 listUser·p0.00:   2.585 ms/op
                 listUser·p0.50:   7.815 ms/op
                 listUser·p0.90:   11.289 ms/op
                 listUser·p0.95:   13.661 ms/op
                 listUser·p0.99:   27.074 ms/op
                 listUser·p0.999:  52.542 ms/op
                 listUser·p0.9999: 55.640 ms/op
                 listUser·p1.00:   55.640 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3830
  mean =      8.707 ±(99.9%) 0.247 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 133 
    [ 5.000, 10.000) = 2968 
    [10.000, 15.000) = 593 
    [15.000, 20.000) = 63 
    [20.000, 25.000) = 34 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 7 
    [45.000, 50.000) = 11 
    [50.000, 55.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.585 ms/op
     p(50.0000) =      7.815 ms/op
     p(90.0000) =     11.289 ms/op
     p(95.0000) =     13.661 ms/op
     p(99.0000) =     27.074 ms/op
     p(99.9000) =     52.542 ms/op
     p(99.9900) =     55.640 ms/op
     p(99.9990) =     55.640 ms/op
     p(99.9999) =     55.640 ms/op
    p(100.0000) =     55.640 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.593          ops/ms
Client.existUser                       thrpt         13.283          ops/ms
Client.getUser                         thrpt          9.898          ops/ms
Client.listUser                        thrpt          3.957          ops/ms
Client.createUser                       avgt          2.976           ms/op
Client.existUser                        avgt          1.757           ms/op
Client.getUser                          avgt          3.063           ms/op
Client.listUser                         avgt          7.224           ms/op
Client.createUser                     sample  10840   2.950 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.065           ms/op
Client.createUser:createUser·p0.50    sample          2.716           ms/op
Client.createUser:createUser·p0.90    sample          3.498           ms/op
Client.createUser:createUser·p0.95    sample          3.977           ms/op
Client.createUser:createUser·p0.99    sample          7.900           ms/op
Client.createUser:createUser·p0.999   sample         20.939           ms/op
Client.createUser:createUser·p0.9999  sample         22.378           ms/op
Client.createUser:createUser·p1.00    sample         22.381           ms/op
Client.existUser                      sample  16701   1.915 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.553           ms/op
Client.existUser:existUser·p0.50      sample          1.759           ms/op
Client.existUser:existUser·p0.90      sample          2.597           ms/op
Client.existUser:existUser·p0.95      sample          2.879           ms/op
Client.existUser:existUser·p0.99      sample          3.572           ms/op
Client.existUser:existUser·p0.999     sample          6.218           ms/op
Client.existUser:existUser·p0.9999    sample          7.181           ms/op
Client.existUser:existUser·p1.00      sample          7.307           ms/op
Client.getUser                        sample  11706   2.726 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.604           ms/op
Client.getUser:getUser·p0.50          sample          2.609           ms/op
Client.getUser:getUser·p0.90          sample          3.401           ms/op
Client.getUser:getUser·p0.95          sample          3.699           ms/op
Client.getUser:getUser·p0.99          sample          6.170           ms/op
Client.getUser:getUser·p0.999         sample         15.270           ms/op
Client.getUser:getUser·p0.9999        sample         15.647           ms/op
Client.getUser:getUser·p1.00          sample         15.647           ms/op
Client.listUser                       sample   3830   8.707 ± 0.247   ms/op
Client.listUser:listUser·p0.00        sample          2.585           ms/op
Client.listUser:listUser·p0.50        sample          7.815           ms/op
Client.listUser:listUser·p0.90        sample         11.289           ms/op
Client.listUser:listUser·p0.95        sample         13.661           ms/op
Client.listUser:listUser·p0.99        sample         27.074           ms/op
Client.listUser:listUser·p0.999       sample         52.542           ms/op
Client.listUser:listUser·p0.9999      sample         55.640           ms/op
Client.listUser:listUser·p1.00        sample         55.640           ms/op
