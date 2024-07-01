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
# Warmup Iteration   1: 1.804 ops/ms
Iteration   1: 7.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.079 ops/ms


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
# Warmup Iteration   1: 6.338 ops/ms
Iteration   1: 14.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.012 ops/ms


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
# Warmup Iteration   1: 6.977 ops/ms
Iteration   1: 12.972 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.972 ops/ms


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
# Warmup Iteration   1: 6.183 ops/ms
Iteration   1: 8.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.146 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.734 ±(99.9%) 0.071 ms/op
Iteration   1: 2.312 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.312 ms/op


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
# Warmup Iteration   1: 3.057 ±(99.9%) 0.050 ms/op
Iteration   1: 1.814 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.814 ms/op


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
# Warmup Iteration   1: 3.186 ±(99.9%) 0.060 ms/op
Iteration   1: 1.832 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.832 ms/op


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.094 ms/op
Iteration   1: 3.416 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.416 ms/op


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
# Warmup Iteration   1: 3.404 ±(99.9%) 0.084 ms/op
Iteration   1: 2.283 ±(99.9%) 0.064 ms/op
                 createUser·p0.00:   0.477 ms/op
                 createUser·p0.50:   2.097 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.757 ms/op
                 createUser·p0.99:   4.423 ms/op
                 createUser·p0.999:  44.301 ms/op
                 createUser·p0.9999: 44.564 ms/op
                 createUser·p1.00:   44.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14008
  mean =      2.283 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13872 
    [ 5.000, 10.000) = 72 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      4.423 ms/op
     p(99.9000) =     44.301 ms/op
     p(99.9900) =     44.564 ms/op
     p(99.9990) =     44.564 ms/op
     p(99.9999) =     44.564 ms/op
    p(100.0000) =     44.564 ms/op


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
# Warmup Iteration   1: 2.824 ±(99.9%) 0.064 ms/op
Iteration   1: 1.740 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.362 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   2.167 ms/op
                 existUser·p0.95:   2.331 ms/op
                 existUser·p0.99:   2.972 ms/op
                 existUser·p0.999:  10.109 ms/op
                 existUser·p0.9999: 10.587 ms/op
                 existUser·p1.00:   10.600 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18375
  mean =      1.740 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1565 
    [ 1.250,  2.500) = 16282 
    [ 2.500,  3.750) = 425 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.362 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.331 ms/op
     p(99.0000) =      2.972 ms/op
     p(99.9000) =     10.109 ms/op
     p(99.9900) =     10.587 ms/op
     p(99.9990) =     10.600 ms/op
     p(99.9999) =     10.600 ms/op
    p(100.0000) =     10.600 ms/op


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
# Warmup Iteration   1: 3.460 ±(99.9%) 0.081 ms/op
Iteration   1: 2.433 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   2.367 ms/op
                 getUser·p0.90:   2.863 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  21.987 ms/op
                 getUser·p0.9999: 22.097 ms/op
                 getUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13320
  mean =      2.433 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8296 
    [ 2.500,  5.000) = 4838 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.367 ms/op
     p(90.0000) =      2.863 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     22.097 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.123 ms/op
Iteration   1: 3.315 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.084 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.915 ms/op
                 listUser·p0.999:  13.232 ms/op
                 listUser·p0.9999: 17.891 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9641
  mean =      3.315 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1658 
    [ 2.500,  3.750) = 5096 
    [ 3.750,  5.000) = 2566 
    [ 5.000,  6.250) = 178 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.915 ms/op
     p(99.9000) =     13.232 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.079          ops/ms
ClientSimple.existUser                       thrpt         14.012          ops/ms
ClientSimple.getUser                         thrpt         12.972          ops/ms
ClientSimple.listUser                        thrpt          8.146          ops/ms
ClientSimple.createUser                       avgt          2.312           ms/op
ClientSimple.existUser                        avgt          1.814           ms/op
ClientSimple.getUser                          avgt          1.832           ms/op
ClientSimple.listUser                         avgt          3.416           ms/op
ClientSimple.createUser                     sample  14008   2.283 ± 0.064   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.477           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.097           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.757           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.423           ms/op
ClientSimple.createUser:createUser·p0.999   sample         44.301           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         44.564           ms/op
ClientSimple.createUser:createUser·p1.00    sample         44.564           ms/op
ClientSimple.existUser                      sample  18375   1.740 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.362           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.681           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.167           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.331           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.972           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.109           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.587           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.600           ms/op
ClientSimple.getUser                        sample  13320   2.433 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.787           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.367           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.076           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.382           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.987           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.097           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.118           ms/op
ClientSimple.listUser                       sample   9641   3.315 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.046           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.084           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.915           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.232           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.891           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.891           ms/op

Benchmark result is saved to 1719793140357.json
