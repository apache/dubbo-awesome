# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.109 ops/ms
Iteration   1: 2.280 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.280 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.712 ops/ms
Iteration   1: 6.643 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.643 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.370 ops/ms
Iteration   1: 5.478 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.478 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.964 ops/ms
Iteration   1: 1.395 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.395 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 14.665 ±(99.9%) 0.292 ms/op
Iteration   1: 6.956 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.956 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.519 ±(99.9%) 0.099 ms/op
Iteration   1: 3.313 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.313 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.126 ±(99.9%) 0.107 ms/op
Iteration   1: 4.512 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.512 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 24.455 ±(99.9%) 0.588 ms/op
Iteration   1: 16.875 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.875 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.233 ±(99.9%) 0.289 ms/op
Iteration   1: 5.794 ±(99.9%) 0.103 ms/op
                 createUser·p0.00:   1.835 ms/op
                 createUser·p0.50:   5.603 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   9.961 ms/op
                 createUser·p0.99:   16.138 ms/op
                 createUser·p0.999:  16.648 ms/op
                 createUser·p0.9999: 16.744 ms/op
                 createUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5544
  mean =      5.794 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 226 
    [ 2.500,  3.750) = 302 
    [ 3.750,  5.000) = 595 
    [ 5.000,  6.250) = 3777 
    [ 6.250,  7.500) = 247 
    [ 7.500,  8.750) = 91 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 125 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.835 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      6.439 ms/op
     p(95.0000) =      9.961 ms/op
     p(99.0000) =     16.138 ms/op
     p(99.9000) =     16.648 ms/op
     p(99.9900) =     16.744 ms/op
     p(99.9990) =     16.744 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.080 ±(99.9%) 0.190 ms/op
Iteration   1: 3.135 ±(99.9%) 0.049 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   10.813 ms/op
                 existUser·p0.999:  12.845 ms/op
                 existUser·p0.9999: 12.861 ms/op
                 existUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10317
  mean =      3.135 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 1326 
    [ 2.500,  3.750) = 8193 
    [ 3.750,  5.000) = 321 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =     10.813 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     12.861 ms/op
     p(99.9999) =     12.861 ms/op
    p(100.0000) =     12.861 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 8.521 ±(99.9%) 0.370 ms/op
Iteration   1: 5.274 ±(99.9%) 0.068 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.709 ms/op
                 getUser·p0.95:   7.515 ms/op
                 getUser·p0.99:   10.027 ms/op
                 getUser·p0.999:  21.685 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6111
  mean =      5.274 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 2646 
    [ 5.000,  7.500) = 3135 
    [ 7.500, 10.000) = 238 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.709 ms/op
     p(95.0000) =      7.515 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     21.685 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 23.918 ±(99.9%) 0.712 ms/op
Iteration   1: 17.229 ±(99.9%) 0.355 ms/op
                 listUser·p0.00:   6.267 ms/op
                 listUser·p0.50:   17.891 ms/op
                 listUser·p0.90:   21.280 ms/op
                 listUser·p0.95:   21.987 ms/op
                 listUser·p0.99:   37.618 ms/op
                 listUser·p0.999:  44.165 ms/op
                 listUser·p0.9999: 49.676 ms/op
                 listUser·p1.00:   49.676 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1875
  mean =     17.229 ±(99.9%) 0.355 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 95 
    [10.000, 15.000) = 421 
    [15.000, 20.000) = 988 
    [20.000, 25.000) = 336 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      6.267 ms/op
     p(50.0000) =     17.891 ms/op
     p(90.0000) =     21.280 ms/op
     p(95.0000) =     21.987 ms/op
     p(99.0000) =     37.618 ms/op
     p(99.9000) =     44.165 ms/op
     p(99.9900) =     49.676 ms/op
     p(99.9990) =     49.676 ms/op
     p(99.9999) =     49.676 ms/op
    p(100.0000) =     49.676 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.280          ops/ms
Client.existUser                       thrpt          6.643          ops/ms
Client.getUser                         thrpt          5.478          ops/ms
Client.listUser                        thrpt          1.395          ops/ms
Client.createUser                       avgt          6.956           ms/op
Client.existUser                        avgt          3.313           ms/op
Client.getUser                          avgt          4.512           ms/op
Client.listUser                         avgt         16.875           ms/op
Client.createUser                     sample   5544   5.794 ± 0.103   ms/op
Client.createUser:createUser·p0.00    sample          1.835           ms/op
Client.createUser:createUser·p0.50    sample          5.603           ms/op
Client.createUser:createUser·p0.90    sample          6.439           ms/op
Client.createUser:createUser·p0.95    sample          9.961           ms/op
Client.createUser:createUser·p0.99    sample         16.138           ms/op
Client.createUser:createUser·p0.999   sample         16.648           ms/op
Client.createUser:createUser·p0.9999  sample         16.744           ms/op
Client.createUser:createUser·p1.00    sample         16.744           ms/op
Client.existUser                      sample  10317   3.135 ± 0.049   ms/op
Client.existUser:existUser·p0.00      sample          0.953           ms/op
Client.existUser:existUser·p0.50      sample          2.863           ms/op
Client.existUser:existUser·p0.90      sample          3.408           ms/op
Client.existUser:existUser·p0.95      sample          4.719           ms/op
Client.existUser:existUser·p0.99      sample         10.813           ms/op
Client.existUser:existUser·p0.999     sample         12.845           ms/op
Client.existUser:existUser·p0.9999    sample         12.861           ms/op
Client.existUser:existUser·p1.00      sample         12.861           ms/op
Client.getUser                        sample   6111   5.274 ± 0.068   ms/op
Client.getUser:getUser·p0.00          sample          1.491           ms/op
Client.getUser:getUser·p0.50          sample          5.087           ms/op
Client.getUser:getUser·p0.90          sample          6.709           ms/op
Client.getUser:getUser·p0.95          sample          7.515           ms/op
Client.getUser:getUser·p0.99          sample         10.027           ms/op
Client.getUser:getUser·p0.999         sample         21.685           ms/op
Client.getUser:getUser·p0.9999        sample         22.413           ms/op
Client.getUser:getUser·p1.00          sample         22.413           ms/op
Client.listUser                       sample   1875  17.229 ± 0.355   ms/op
Client.listUser:listUser·p0.00        sample          6.267           ms/op
Client.listUser:listUser·p0.50        sample         17.891           ms/op
Client.listUser:listUser·p0.90        sample         21.280           ms/op
Client.listUser:listUser·p0.95        sample         21.987           ms/op
Client.listUser:listUser·p0.99        sample         37.618           ms/op
Client.listUser:listUser·p0.999       sample         44.165           ms/op
Client.listUser:listUser·p0.9999      sample         49.676           ms/op
Client.listUser:listUser·p1.00        sample         49.676           ms/op
