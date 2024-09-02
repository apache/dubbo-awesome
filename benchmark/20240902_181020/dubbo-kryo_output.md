# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.521 ops/ms
Iteration   1: 7.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.355 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.487 ops/ms
Iteration   1: 12.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.779 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.109 ops/ms
Iteration   1: 12.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.074 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.926 ops/ms
Iteration   1: 8.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.796 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.521 ±(99.9%) 0.059 ms/op
Iteration   1: 2.164 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.164 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.287 ±(99.9%) 0.050 ms/op
Iteration   1: 1.777 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.777 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.995 ±(99.9%) 0.068 ms/op
Iteration   1: 1.997 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.997 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.711 ±(99.9%) 0.109 ms/op
Iteration   1: 2.953 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.953 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.730 ±(99.9%) 0.106 ms/op
Iteration   1: 2.300 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.448 ms/op
                 createUser·p0.50:   2.175 ms/op
                 createUser·p0.90:   2.761 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  14.469 ms/op
                 createUser·p0.9999: 20.187 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13901
  mean =      2.300 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10718 
    [ 2.500,  5.000) = 2986 
    [ 5.000,  7.500) = 120 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.448 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      2.761 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     14.469 ms/op
     p(99.9900) =     20.187 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.000 ±(99.9%) 0.064 ms/op
Iteration   1: 1.984 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   1.864 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.593 ms/op
                 existUser·p0.99:   4.764 ms/op
                 existUser·p0.999:  27.722 ms/op
                 existUser·p0.9999: 27.898 ms/op
                 existUser·p1.00:   27.918 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16106
  mean =      1.984 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15055 
    [ 2.500,  5.000) = 933 
    [ 5.000,  7.500) = 22 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.864 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      4.764 ms/op
     p(99.9000) =     27.722 ms/op
     p(99.9900) =     27.898 ms/op
     p(99.9990) =     27.918 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.089 ±(99.9%) 0.078 ms/op
Iteration   1: 1.789 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.761 ms/op
                 getUser·p0.50:   1.712 ms/op
                 getUser·p0.90:   2.195 ms/op
                 getUser·p0.95:   2.327 ms/op
                 getUser·p0.99:   3.279 ms/op
                 getUser·p0.999:  11.256 ms/op
                 getUser·p0.9999: 11.396 ms/op
                 getUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17871
  mean =      1.789 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 344 
    [ 1.250,  2.500) = 17065 
    [ 2.500,  3.750) = 352 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      1.712 ms/op
     p(90.0000) =      2.195 ms/op
     p(95.0000) =      2.327 ms/op
     p(99.0000) =      3.279 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     11.396 ms/op
     p(99.9990) =     11.551 ms/op
     p(99.9999) =     11.551 ms/op
    p(100.0000) =     11.551 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.564 ±(99.9%) 0.135 ms/op
Iteration   1: 3.015 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   2.834 ms/op
                 listUser·p0.90:   3.690 ms/op
                 listUser·p0.95:   4.067 ms/op
                 listUser·p0.99:   5.915 ms/op
                 listUser·p0.999:  7.327 ms/op
                 listUser·p0.9999: 8.949 ms/op
                 listUser·p1.00:   8.995 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10602
  mean =      3.015 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 2 
    [1.500, 2.000) = 64 
    [2.000, 2.500) = 714 
    [2.500, 3.000) = 6104 
    [3.000, 3.500) = 2092 
    [3.500, 4.000) = 1028 
    [4.000, 4.500) = 347 
    [4.500, 5.000) = 79 
    [5.000, 5.500) = 25 
    [5.500, 6.000) = 54 
    [6.000, 6.500) = 38 
    [6.500, 7.000) = 18 
    [7.000, 7.500) = 32 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =      7.327 ms/op
     p(99.9900) =      8.949 ms/op
     p(99.9990) =      8.995 ms/op
     p(99.9999) =      8.995 ms/op
    p(100.0000) =      8.995 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.355          ops/ms
ClientSimple.existUser                       thrpt         12.779          ops/ms
ClientSimple.getUser                         thrpt         12.074          ops/ms
ClientSimple.listUser                        thrpt          8.796          ops/ms
ClientSimple.createUser                       avgt          2.164           ms/op
ClientSimple.existUser                        avgt          1.777           ms/op
ClientSimple.getUser                          avgt          1.997           ms/op
ClientSimple.listUser                         avgt          2.953           ms/op
ClientSimple.createUser                     sample  13901   2.300 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.448           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.175           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.761           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.084           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.439           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.469           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.187           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.251           ms/op
ClientSimple.existUser                      sample  16106   1.984 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.585           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.864           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.764           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.722           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.898           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.918           ms/op
ClientSimple.getUser                        sample  17871   1.789 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.761           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.712           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.195           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.327           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.279           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.256           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.396           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.551           ms/op
ClientSimple.listUser                       sample  10602   3.015 ± 0.020   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.294           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.834           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.690           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.067           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.915           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.327           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.949           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.995           ms/op

Benchmark result is saved to 1725300334626.json
