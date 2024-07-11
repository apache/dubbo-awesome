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
# Warmup Iteration   1: 0.544 ops/ms
Iteration   1: 4.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  4.446 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.910 ops/ms
Iteration   1: 8.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  8.476 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.421 ops/ms
Iteration   1: 10.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.728 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.632 ops/ms
Iteration   1: 5.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  5.628 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.793 ±(99.9%) 0.147 ms/op
Iteration   1: 3.467 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  3.467 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 4.534 ±(99.9%) 0.110 ms/op
Iteration   1: 2.754 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.754 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.136 ±(99.9%) 0.111 ms/op
Iteration   1: 3.292 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  3.292 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.817 ±(99.9%) 0.157 ms/op
Iteration   1: 4.971 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.971 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 5.595 ±(99.9%) 0.215 ms/op
Iteration   1: 3.101 ±(99.9%) 0.106 ms/op
                 createUser·p0.00:   0.470 ms/op
                 createUser·p0.50:   2.335 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   6.816 ms/op
                 createUser·p0.99:   11.026 ms/op
                 createUser·p0.999:  53.281 ms/op
                 createUser·p0.9999: 54.911 ms/op
                 createUser·p1.00:   54.919 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 10329
  mean =      3.101 ±(99.9%) 0.106 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9353 
    [ 5.000, 10.000) = 804 
    [10.000, 15.000) = 109 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      2.335 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      6.816 ms/op
     p(99.0000) =     11.026 ms/op
     p(99.9000) =     53.281 ms/op
     p(99.9900) =     54.911 ms/op
     p(99.9990) =     54.919 ms/op
     p(99.9999) =     54.919 ms/op
    p(100.0000) =     54.919 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.979 ±(99.9%) 0.204 ms/op
Iteration   1: 2.863 ±(99.9%) 0.054 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.322 ms/op
                 existUser·p0.90:   4.739 ms/op
                 existUser·p0.95:   5.661 ms/op
                 existUser·p0.99:   9.396 ms/op
                 existUser·p0.999:  16.606 ms/op
                 existUser·p0.9999: 17.245 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 11224
  mean =      2.863 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 6144 
    [ 2.500,  3.750) = 2878 
    [ 3.750,  5.000) = 1058 
    [ 5.000,  6.250) = 626 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 96 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.322 ms/op
     p(90.0000) =      4.739 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      9.396 ms/op
     p(99.9000) =     16.606 ms/op
     p(99.9900) =     17.245 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 5.933 ±(99.9%) 0.224 ms/op
Iteration   1: 2.652 ±(99.9%) 0.057 ms/op
                 getUser·p0.00:   0.373 ms/op
                 getUser·p0.50:   2.175 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   5.445 ms/op
                 getUser·p0.99:   12.354 ms/op
                 getUser·p0.999:  19.873 ms/op
                 getUser·p0.9999: 30.210 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12282
  mean =      2.652 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8767 
    [ 2.500,  5.000) = 2786 
    [ 5.000,  7.500) = 417 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      5.445 ms/op
     p(99.0000) =     12.354 ms/op
     p(99.9000) =     19.873 ms/op
     p(99.9900) =     30.210 ms/op
     p(99.9990) =     30.278 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 6.118 ±(99.9%) 0.219 ms/op
Iteration   1: 4.621 ±(99.9%) 0.123 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   7.217 ms/op
                 listUser·p0.95:   8.826 ms/op
                 listUser·p0.99:   22.673 ms/op
                 listUser·p0.999:  32.245 ms/op
                 listUser·p0.9999: 33.620 ms/op
                 listUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 6905
  mean =      4.621 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 289 
    [ 2.500,  5.000) = 4892 
    [ 5.000,  7.500) = 1154 
    [ 7.500, 10.000) = 360 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      7.217 ms/op
     p(95.0000) =      8.826 ms/op
     p(99.0000) =     22.673 ms/op
     p(99.9000) =     32.245 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# Run complete. Total time: 00:01:35

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          4.446          ops/ms
ClientSimple.existUser                       thrpt          8.476          ops/ms
ClientSimple.getUser                         thrpt         10.728          ops/ms
ClientSimple.listUser                        thrpt          5.628          ops/ms
ClientSimple.createUser                       avgt          3.467           ms/op
ClientSimple.existUser                        avgt          2.754           ms/op
ClientSimple.getUser                          avgt          3.292           ms/op
ClientSimple.listUser                         avgt          4.971           ms/op
ClientSimple.createUser                     sample  10329   3.101 ± 0.106   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.470           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.335           ms/op
ClientSimple.createUser:createUser·p0.90    sample          4.841           ms/op
ClientSimple.createUser:createUser·p0.95    sample          6.816           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.026           ms/op
ClientSimple.createUser:createUser·p0.999   sample         53.281           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         54.911           ms/op
ClientSimple.createUser:createUser·p1.00    sample         54.919           ms/op
ClientSimple.existUser                      sample  11224   2.863 ± 0.054   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.856           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.90      sample          4.739           ms/op
ClientSimple.existUser:existUser·p0.95      sample          5.661           ms/op
ClientSimple.existUser:existUser·p0.99      sample          9.396           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.606           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.245           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.269           ms/op
ClientSimple.getUser                        sample  12282   2.652 ± 0.057   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.373           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.175           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.785           ms/op
ClientSimple.getUser:getUser·p0.95          sample          5.445           ms/op
ClientSimple.getUser:getUser·p0.99          sample         12.354           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.873           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.210           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.278           ms/op
ClientSimple.listUser                       sample   6905   4.621 ± 0.123   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.135           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.883           ms/op
ClientSimple.listUser:listUser·p0.90        sample          7.217           ms/op
ClientSimple.listUser:listUser·p0.95        sample          8.826           ms/op
ClientSimple.listUser:listUser·p0.99        sample         22.673           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.245           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         33.620           ms/op
ClientSimple.listUser:listUser·p1.00        sample         33.620           ms/op

Benchmark result is saved to 1720677960474.json
