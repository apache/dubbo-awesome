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
# Warmup Iteration   1: 0.884 ops/ms
Iteration   1: 1.956 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.956 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 1.963 ops/ms
Iteration   1: 3.744 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.744 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.485 ops/ms
Iteration   1: 3.871 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.871 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 0.636 ops/ms
Iteration   1: 1.152 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.152 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 25.940 ±(99.9%) 0.523 ms/op
Iteration   1: 13.620 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  13.620 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 11.924 ±(99.9%) 0.151 ms/op
Iteration   1: 5.354 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.354 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.491 ±(99.9%) 0.193 ms/op
Iteration   1: 5.914 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.914 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 36.938 ±(99.9%) 1.174 ms/op
Iteration   1: 23.403 ±(99.9%) 0.214 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  23.403 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 16.211 ±(99.9%) 0.653 ms/op
Iteration   1: 8.766 ±(99.9%) 0.154 ms/op
                 createUser·p0.00:   2.071 ms/op
                 createUser·p0.50:   8.323 ms/op
                 createUser·p0.90:   10.266 ms/op
                 createUser·p0.95:   15.401 ms/op
                 createUser·p0.99:   21.245 ms/op
                 createUser·p0.999:  27.122 ms/op
                 createUser·p0.9999: 27.197 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3657
  mean =      8.766 ±(99.9%) 0.154 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 54 
    [ 5.000,  7.500) = 857 
    [ 7.500, 10.000) = 2343 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.071 ms/op
     p(50.0000) =      8.323 ms/op
     p(90.0000) =     10.266 ms/op
     p(95.0000) =     15.401 ms/op
     p(99.0000) =     21.245 ms/op
     p(99.9000) =     27.122 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.856 ±(99.9%) 0.312 ms/op
Iteration   1: 5.551 ±(99.9%) 0.114 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   5.235 ms/op
                 existUser·p0.90:   6.155 ms/op
                 existUser·p0.95:   8.307 ms/op
                 existUser·p0.99:   18.711 ms/op
                 existUser·p0.999:  32.333 ms/op
                 existUser·p0.9999: 33.817 ms/op
                 existUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 5756
  mean =      5.551 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 172 
    [ 2.500,  5.000) = 1199 
    [ 5.000,  7.500) = 4020 
    [ 7.500, 10.000) = 188 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      6.155 ms/op
     p(95.0000) =      8.307 ms/op
     p(99.0000) =     18.711 ms/op
     p(99.9000) =     32.333 ms/op
     p(99.9900) =     33.817 ms/op
     p(99.9990) =     33.817 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 16.219 ±(99.9%) 0.603 ms/op
Iteration   1: 7.191 ±(99.9%) 0.165 ms/op
                 getUser·p0.00:   2.974 ms/op
                 getUser·p0.50:   6.488 ms/op
                 getUser·p0.90:   9.617 ms/op
                 getUser·p0.95:   10.682 ms/op
                 getUser·p0.99:   26.097 ms/op
                 getUser·p0.999:  34.182 ms/op
                 getUser·p0.9999: 34.406 ms/op
                 getUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4428
  mean =      7.191 ±(99.9%) 0.165 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 418 
    [ 5.000,  7.500) = 2759 
    [ 7.500, 10.000) = 920 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.974 ms/op
     p(50.0000) =      6.488 ms/op
     p(90.0000) =      9.617 ms/op
     p(95.0000) =     10.682 ms/op
     p(99.0000) =     26.097 ms/op
     p(99.9000) =     34.182 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 36.739 ±(99.9%) 1.888 ms/op
Iteration   1: 23.299 ±(99.9%) 0.399 ms/op
                 listUser·p0.00:   12.206 ms/op
                 listUser·p0.50:   22.708 ms/op
                 listUser·p0.90:   28.115 ms/op
                 listUser·p0.95:   30.697 ms/op
                 listUser·p0.99:   34.367 ms/op
                 listUser·p0.999:  40.026 ms/op
                 listUser·p0.9999: 42.074 ms/op
                 listUser·p1.00:   42.074 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1371
  mean =     23.299 ±(99.9%) 0.399 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 265 
    [20.000, 22.500) = 287 
    [22.500, 25.000) = 162 
    [25.000, 27.500) = 256 
    [27.500, 30.000) = 207 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 8 
    [37.500, 40.000) = 0 
    [40.000, 42.500) = 1 
    [42.500, 45.000) = 0 
    [45.000, 47.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =     12.206 ms/op
     p(50.0000) =     22.708 ms/op
     p(90.0000) =     28.115 ms/op
     p(95.0000) =     30.697 ms/op
     p(99.0000) =     34.367 ms/op
     p(99.9000) =     40.026 ms/op
     p(99.9900) =     42.074 ms/op
     p(99.9990) =     42.074 ms/op
     p(99.9999) =     42.074 ms/op
    p(100.0000) =     42.074 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.956          ops/ms
Client.existUser                       thrpt         3.744          ops/ms
Client.getUser                         thrpt         3.871          ops/ms
Client.listUser                        thrpt         1.152          ops/ms
Client.createUser                       avgt        13.620           ms/op
Client.existUser                        avgt         5.354           ms/op
Client.getUser                          avgt         5.914           ms/op
Client.listUser                         avgt        23.403           ms/op
Client.createUser                     sample  3657   8.766 ± 0.154   ms/op
Client.createUser:createUser·p0.00    sample         2.071           ms/op
Client.createUser:createUser·p0.50    sample         8.323           ms/op
Client.createUser:createUser·p0.90    sample        10.266           ms/op
Client.createUser:createUser·p0.95    sample        15.401           ms/op
Client.createUser:createUser·p0.99    sample        21.245           ms/op
Client.createUser:createUser·p0.999   sample        27.122           ms/op
Client.createUser:createUser·p0.9999  sample        27.197           ms/op
Client.createUser:createUser·p1.00    sample        27.197           ms/op
Client.existUser                      sample  5756   5.551 ± 0.114   ms/op
Client.existUser:existUser·p0.00      sample         0.947           ms/op
Client.existUser:existUser·p0.50      sample         5.235           ms/op
Client.existUser:existUser·p0.90      sample         6.155           ms/op
Client.existUser:existUser·p0.95      sample         8.307           ms/op
Client.existUser:existUser·p0.99      sample        18.711           ms/op
Client.existUser:existUser·p0.999     sample        32.333           ms/op
Client.existUser:existUser·p0.9999    sample        33.817           ms/op
Client.existUser:existUser·p1.00      sample        33.817           ms/op
Client.getUser                        sample  4428   7.191 ± 0.165   ms/op
Client.getUser:getUser·p0.00          sample         2.974           ms/op
Client.getUser:getUser·p0.50          sample         6.488           ms/op
Client.getUser:getUser·p0.90          sample         9.617           ms/op
Client.getUser:getUser·p0.95          sample        10.682           ms/op
Client.getUser:getUser·p0.99          sample        26.097           ms/op
Client.getUser:getUser·p0.999         sample        34.182           ms/op
Client.getUser:getUser·p0.9999        sample        34.406           ms/op
Client.getUser:getUser·p1.00          sample        34.406           ms/op
Client.listUser                       sample  1371  23.299 ± 0.399   ms/op
Client.listUser:listUser·p0.00        sample        12.206           ms/op
Client.listUser:listUser·p0.50        sample        22.708           ms/op
Client.listUser:listUser·p0.90        sample        28.115           ms/op
Client.listUser:listUser·p0.95        sample        30.697           ms/op
Client.listUser:listUser·p0.99        sample        34.367           ms/op
Client.listUser:listUser·p0.999       sample        40.026           ms/op
Client.listUser:listUser·p0.9999      sample        42.074           ms/op
Client.listUser:listUser·p1.00        sample        42.074           ms/op
