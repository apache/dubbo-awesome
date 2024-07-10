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
# Warmup Iteration   1: 1.703 ops/ms
Iteration   1: 7.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.083 ops/ms


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
# Warmup Iteration   1: 6.247 ops/ms
Iteration   1: 14.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.010 ops/ms


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
# Warmup Iteration   1: 4.658 ops/ms
Iteration   1: 12.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.237 ops/ms


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
# Warmup Iteration   1: 4.921 ops/ms
Iteration   1: 8.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.204 ops/ms


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
# Warmup Iteration   1: 3.927 ±(99.9%) 0.068 ms/op
Iteration   1: 2.082 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.082 ms/op


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
# Warmup Iteration   1: 2.912 ±(99.9%) 0.054 ms/op
Iteration   1: 2.101 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.187 ±(99.9%) 0.053 ms/op
Iteration   1: 2.080 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.080 ms/op


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
# Warmup Iteration   1: 4.822 ±(99.9%) 0.094 ms/op
Iteration   1: 3.402 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.402 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.077 ms/op
Iteration   1: 2.176 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   1.958 ms/op
                 createUser·p0.90:   2.593 ms/op
                 createUser·p0.95:   2.765 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  33.882 ms/op
                 createUser·p0.9999: 35.785 ms/op
                 createUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14767
  mean =      2.176 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12700 
    [ 2.500,  5.000) = 1902 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     33.882 ms/op
     p(99.9900) =     35.785 ms/op
     p(99.9990) =     36.504 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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
# Warmup Iteration   1: 2.906 ±(99.9%) 0.071 ms/op
Iteration   1: 1.754 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   1.686 ms/op
                 existUser·p0.90:   2.154 ms/op
                 existUser·p0.95:   2.286 ms/op
                 existUser·p0.99:   3.236 ms/op
                 existUser·p0.999:  11.105 ms/op
                 existUser·p0.9999: 11.455 ms/op
                 existUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18222
  mean =      1.754 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 922 
    [ 1.250,  2.500) = 16849 
    [ 2.500,  3.750) = 364 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      1.686 ms/op
     p(90.0000) =      2.154 ms/op
     p(95.0000) =      2.286 ms/op
     p(99.0000) =      3.236 ms/op
     p(99.9000) =     11.105 ms/op
     p(99.9900) =     11.455 ms/op
     p(99.9990) =     11.469 ms/op
     p(99.9999) =     11.469 ms/op
    p(100.0000) =     11.469 ms/op


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
# Warmup Iteration   1: 3.359 ±(99.9%) 0.087 ms/op
Iteration   1: 2.109 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   2.042 ms/op
                 getUser·p0.90:   2.626 ms/op
                 getUser·p0.95:   2.822 ms/op
                 getUser·p0.99:   3.872 ms/op
                 getUser·p0.999:  11.485 ms/op
                 getUser·p0.9999: 11.665 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15159
  mean =      2.109 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 12714 
    [ 2.500,  3.750) = 2162 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.872 ms/op
     p(99.9000) =     11.485 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     11.665 ms/op
     p(99.9999) =     11.665 ms/op
    p(100.0000) =     11.665 ms/op


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.137 ms/op
Iteration   1: 3.423 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.287 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   6.182 ms/op
                 listUser·p0.999:  21.343 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9330
  mean =      3.423 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2021 
    [ 2.500,  5.000) = 6989 
    [ 5.000,  7.500) = 281 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.287 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.182 ms/op
     p(99.9000) =     21.343 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.083          ops/ms
ClientSimple.existUser                       thrpt         14.010          ops/ms
ClientSimple.getUser                         thrpt         12.237          ops/ms
ClientSimple.listUser                        thrpt          8.204          ops/ms
ClientSimple.createUser                       avgt          2.082           ms/op
ClientSimple.existUser                        avgt          2.101           ms/op
ClientSimple.getUser                          avgt          2.080           ms/op
ClientSimple.listUser                         avgt          3.402           ms/op
ClientSimple.createUser                     sample  14767   2.176 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.674           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.958           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.593           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.612           ms/op
ClientSimple.createUser:createUser·p0.999   sample         33.882           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.785           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.504           ms/op
ClientSimple.existUser                      sample  18222   1.754 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.659           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.686           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.154           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.236           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.105           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.455           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.469           ms/op
ClientSimple.getUser                        sample  15159   2.109 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.835           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.042           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.626           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.822           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.872           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.485           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.665           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.665           ms/op
ClientSimple.listUser                       sample   9330   3.423 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.178           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.287           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.735           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.182           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.343           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.660           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.660           ms/op

Benchmark result is saved to 1720591569141.json
