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
# Warmup Iteration   1: 1.775 ops/ms
Iteration   1: 7.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.044 ops/ms


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
# Warmup Iteration   1: 6.407 ops/ms
Iteration   1: 12.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.789 ops/ms


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
# Warmup Iteration   1: 5.620 ops/ms
Iteration   1: 13.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.750 ops/ms


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
# Warmup Iteration   1: 5.357 ops/ms
Iteration   1: 8.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.180 ops/ms


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.082 ms/op
Iteration   1: 2.226 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.226 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.228 ±(99.9%) 0.052 ms/op
Iteration   1: 1.771 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.771 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.310 ±(99.9%) 0.062 ms/op
Iteration   1: 2.345 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.345 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ±(99.9%) 0.086 ms/op
Iteration   1: 3.154 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.154 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.538 ±(99.9%) 0.085 ms/op
Iteration   1: 2.107 ±(99.9%) 0.067 ms/op
                 createUser·p0.00:   0.545 ms/op
                 createUser·p0.50:   1.769 ms/op
                 createUser·p0.90:   2.286 ms/op
                 createUser·p0.95:   2.617 ms/op
                 createUser·p0.99:   11.701 ms/op
                 createUser·p0.999:  44.237 ms/op
                 createUser·p0.9999: 45.373 ms/op
                 createUser·p1.00:   45.482 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15556
  mean =      2.107 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15261 
    [ 5.000, 10.000) = 133 
    [10.000, 15.000) = 60 
    [15.000, 20.000) = 39 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 18 
    [30.000, 35.000) = 11 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =     11.701 ms/op
     p(99.9000) =     44.237 ms/op
     p(99.9900) =     45.373 ms/op
     p(99.9990) =     45.482 ms/op
     p(99.9999) =     45.482 ms/op
    p(100.0000) =     45.482 ms/op


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
# Warmup Iteration   1: 2.823 ±(99.9%) 0.059 ms/op
Iteration   1: 1.658 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.429 ms/op
                 existUser·p0.50:   1.595 ms/op
                 existUser·p0.90:   2.154 ms/op
                 existUser·p0.95:   2.380 ms/op
                 existUser·p0.99:   2.855 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 11.950 ms/op
                 existUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19397
  mean =      1.658 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2936 
    [ 1.250,  2.500) = 15816 
    [ 2.500,  3.750) = 578 
    [ 3.750,  5.000) = 4 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      1.595 ms/op
     p(90.0000) =      2.154 ms/op
     p(95.0000) =      2.380 ms/op
     p(99.0000) =      2.855 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     11.950 ms/op
     p(99.9990) =     12.042 ms/op
     p(99.9999) =     12.042 ms/op
    p(100.0000) =     12.042 ms/op


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
# Warmup Iteration   1: 3.222 ±(99.9%) 0.087 ms/op
Iteration   1: 1.876 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   1.806 ms/op
                 getUser·p0.90:   2.216 ms/op
                 getUser·p0.95:   2.413 ms/op
                 getUser·p0.99:   2.947 ms/op
                 getUser·p0.999:  12.485 ms/op
                 getUser·p0.9999: 12.740 ms/op
                 getUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17046
  mean =      1.876 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 16331 
    [ 2.500,  3.750) = 564 
    [ 3.750,  5.000) = 25 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.413 ms/op
     p(99.0000) =      2.947 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     12.740 ms/op
     p(99.9990) =     12.763 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


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
# Warmup Iteration   1: 4.748 ±(99.9%) 0.147 ms/op
Iteration   1: 3.735 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.346 ms/op
                 listUser·p0.999:  20.447 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8579
  mean =      3.735 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 514 
    [ 2.500,  5.000) = 7874 
    [ 5.000,  7.500) = 130 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.346 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.044          ops/ms
ClientSimple.existUser                       thrpt         12.789          ops/ms
ClientSimple.getUser                         thrpt         13.750          ops/ms
ClientSimple.listUser                        thrpt          8.180          ops/ms
ClientSimple.createUser                       avgt          2.226           ms/op
ClientSimple.existUser                        avgt          1.771           ms/op
ClientSimple.getUser                          avgt          2.345           ms/op
ClientSimple.listUser                         avgt          3.154           ms/op
ClientSimple.createUser                     sample  15556   2.107 ± 0.067   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.545           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.769           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.286           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.617           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.701           ms/op
ClientSimple.createUser:createUser·p0.999   sample         44.237           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         45.373           ms/op
ClientSimple.createUser:createUser·p1.00    sample         45.482           ms/op
ClientSimple.existUser                      sample  19397   1.658 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.429           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.595           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.154           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.223           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.950           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.042           ms/op
ClientSimple.getUser                        sample  17046   1.876 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.800           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.806           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.216           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.947           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.485           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.740           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.763           ms/op
ClientSimple.listUser                       sample   8579   3.735 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.835           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.703           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.346           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.447           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.808           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.808           ms/op

Benchmark result is saved to 1713247517024.json
