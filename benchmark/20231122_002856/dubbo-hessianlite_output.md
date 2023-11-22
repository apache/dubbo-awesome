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
# Warmup Iteration   1: 2.827 ops/ms
Iteration   1: 6.431 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.431 ops/ms


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
# Warmup Iteration   1: 6.363 ops/ms
Iteration   1: 13.303 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.303 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.404 ops/ms
Iteration   1: 9.631 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.631 ops/ms


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
# Warmup Iteration   1: 2.182 ops/ms
Iteration   1: 3.786 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.786 ops/ms


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
# Warmup Iteration   1: 5.273 ±(99.9%) 0.052 ms/op
Iteration   1: 2.770 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.770 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.049 ms/op
Iteration   1: 2.183 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.183 ms/op


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.037 ms/op
Iteration   1: 2.870 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.870 ms/op


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
# Warmup Iteration   1: 11.271 ±(99.9%) 0.183 ms/op
Iteration   1: 7.490 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.490 ms/op


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
# Warmup Iteration   1: 4.713 ±(99.9%) 0.090 ms/op
Iteration   1: 2.948 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   2.728 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.657 ms/op
                 createUser·p0.999:  12.911 ms/op
                 createUser·p0.9999: 13.809 ms/op
                 createUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10873
  mean =      2.948 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 2620 
    [ 2.500,  3.750) = 7330 
    [ 3.750,  5.000) = 730 
    [ 5.000,  6.250) = 142 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      2.728 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.657 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     13.809 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


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
# Warmup Iteration   1: 2.768 ±(99.9%) 0.052 ms/op
Iteration   1: 1.686 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   1.606 ms/op
                 existUser·p0.90:   1.972 ms/op
                 existUser·p0.95:   2.154 ms/op
                 existUser·p0.99:   3.178 ms/op
                 existUser·p0.999:  25.818 ms/op
                 existUser·p0.9999: 26.581 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19102
  mean =      1.686 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18739 
    [ 2.500,  5.000) = 311 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      1.606 ms/op
     p(90.0000) =      1.972 ms/op
     p(95.0000) =      2.154 ms/op
     p(99.0000) =      3.178 ms/op
     p(99.9000) =     25.818 ms/op
     p(99.9900) =     26.581 ms/op
     p(99.9990) =     26.640 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 4.299 ±(99.9%) 0.077 ms/op
Iteration   1: 2.991 ±(99.9%) 0.043 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.859 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   6.953 ms/op
                 getUser·p0.999:  21.272 ms/op
                 getUser·p0.9999: 21.493 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10820
  mean =      2.991 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3052 
    [ 2.500,  5.000) = 7589 
    [ 5.000,  7.500) = 93 
    [ 7.500, 10.000) = 22 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      6.953 ms/op
     p(99.9000) =     21.272 ms/op
     p(99.9900) =     21.493 ms/op
     p(99.9990) =     21.496 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 11.085 ±(99.9%) 0.372 ms/op
Iteration   1: 7.543 ±(99.9%) 0.144 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   7.029 ms/op
                 listUser·p0.90:   10.011 ms/op
                 listUser·p0.95:   11.105 ms/op
                 listUser·p0.99:   20.269 ms/op
                 listUser·p0.999:  31.042 ms/op
                 listUser·p0.9999: 32.014 ms/op
                 listUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4243
  mean =      7.543 ±(99.9%) 0.144 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 286 
    [ 5.000,  7.500) = 2273 
    [ 7.500, 10.000) = 1256 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.097 ms/op
     p(50.0000) =      7.029 ms/op
     p(90.0000) =     10.011 ms/op
     p(95.0000) =     11.105 ms/op
     p(99.0000) =     20.269 ms/op
     p(99.9000) =     31.042 ms/op
     p(99.9900) =     32.014 ms/op
     p(99.9990) =     32.014 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.431          ops/ms
Client.existUser                       thrpt         13.303          ops/ms
Client.getUser                         thrpt          9.631          ops/ms
Client.listUser                        thrpt          3.786          ops/ms
Client.createUser                       avgt          2.770           ms/op
Client.existUser                        avgt          2.183           ms/op
Client.getUser                          avgt          2.870           ms/op
Client.listUser                         avgt          7.490           ms/op
Client.createUser                     sample  10873   2.948 ± 0.026   ms/op
Client.createUser:createUser·p0.00    sample          1.186           ms/op
Client.createUser:createUser·p0.50    sample          2.728           ms/op
Client.createUser:createUser·p0.90    sample          3.678           ms/op
Client.createUser:createUser·p0.95    sample          3.936           ms/op
Client.createUser:createUser·p0.99    sample          5.657           ms/op
Client.createUser:createUser·p0.999   sample         12.911           ms/op
Client.createUser:createUser·p0.9999  sample         13.809           ms/op
Client.createUser:createUser·p1.00    sample         13.812           ms/op
Client.existUser                      sample  19102   1.686 ± 0.025   ms/op
Client.existUser:existUser·p0.00      sample          0.585           ms/op
Client.existUser:existUser·p0.50      sample          1.606           ms/op
Client.existUser:existUser·p0.90      sample          1.972           ms/op
Client.existUser:existUser·p0.95      sample          2.154           ms/op
Client.existUser:existUser·p0.99      sample          3.178           ms/op
Client.existUser:existUser·p0.999     sample         25.818           ms/op
Client.existUser:existUser·p0.9999    sample         26.581           ms/op
Client.existUser:existUser·p1.00      sample         26.640           ms/op
Client.getUser                        sample  10820   2.991 ± 0.043   ms/op
Client.getUser:getUser·p0.00          sample          0.947           ms/op
Client.getUser:getUser·p0.50          sample          2.859           ms/op
Client.getUser:getUser·p0.90          sample          3.707           ms/op
Client.getUser:getUser·p0.95          sample          3.953           ms/op
Client.getUser:getUser·p0.99          sample          6.953           ms/op
Client.getUser:getUser·p0.999         sample         21.272           ms/op
Client.getUser:getUser·p0.9999        sample         21.493           ms/op
Client.getUser:getUser·p1.00          sample         21.496           ms/op
Client.listUser                       sample   4243   7.543 ± 0.144   ms/op
Client.listUser:listUser·p0.00        sample          2.097           ms/op
Client.listUser:listUser·p0.50        sample          7.029           ms/op
Client.listUser:listUser·p0.90        sample         10.011           ms/op
Client.listUser:listUser·p0.95        sample         11.105           ms/op
Client.listUser:listUser·p0.99        sample         20.269           ms/op
Client.listUser:listUser·p0.999       sample         31.042           ms/op
Client.listUser:listUser·p0.9999      sample         32.014           ms/op
Client.listUser:listUser·p1.00        sample         32.014           ms/op
