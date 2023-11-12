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
# Warmup Iteration   1: 1.084 ops/ms
Iteration   1: 2.794 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.794 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.141 ops/ms
Iteration   1: 7.301 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.301 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.151 ops/ms
Iteration   1: 5.240 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.240 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 0.699 ops/ms
Iteration   1: 1.100 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.100 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 13.017 ±(99.9%) 0.259 ms/op
Iteration   1: 8.656 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  8.656 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 8.889 ±(99.9%) 0.120 ms/op
Iteration   1: 4.276 ±(99.9%) 0.062 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.276 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 12.143 ±(99.9%) 0.233 ms/op
Iteration   1: 5.466 ±(99.9%) 0.054 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.466 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 31.146 ±(99.9%) 1.151 ms/op
Iteration   1: 23.478 ±(99.9%) 0.431 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  23.478 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 10.678 ±(99.9%) 0.306 ms/op
Iteration   1: 7.380 ±(99.9%) 0.259 ms/op
                 createUser·p0.00:   1.841 ms/op
                 createUser·p0.50:   6.152 ms/op
                 createUser·p0.90:   12.567 ms/op
                 createUser·p0.95:   14.959 ms/op
                 createUser·p0.99:   31.228 ms/op
                 createUser·p0.999:  49.657 ms/op
                 createUser·p0.9999: 50.070 ms/op
                 createUser·p1.00:   50.070 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4299
  mean =      7.380 ±(99.9%) 0.259 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1240 
    [ 5.000, 10.000) = 2405 
    [10.000, 15.000) = 445 
    [15.000, 20.000) = 144 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 7 
    [30.000, 35.000) = 25 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 31 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.841 ms/op
     p(50.0000) =      6.152 ms/op
     p(90.0000) =     12.567 ms/op
     p(95.0000) =     14.959 ms/op
     p(99.0000) =     31.228 ms/op
     p(99.9000) =     49.657 ms/op
     p(99.9900) =     50.070 ms/op
     p(99.9990) =     50.070 ms/op
     p(99.9999) =     50.070 ms/op
    p(100.0000) =     50.070 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.039 ±(99.9%) 0.250 ms/op
Iteration   1: 3.238 ±(99.9%) 0.094 ms/op
                 existUser·p0.00:   1.008 ms/op
                 existUser·p0.50:   2.404 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   8.585 ms/op
                 existUser·p0.99:   14.452 ms/op
                 existUser·p0.999:  34.884 ms/op
                 existUser·p0.9999: 43.713 ms/op
                 existUser·p1.00:   43.713 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9791
  mean =      3.238 ±(99.9%) 0.094 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8871 
    [ 5.000, 10.000) = 629 
    [10.000, 15.000) = 212 
    [15.000, 20.000) = 47 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      2.404 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     14.452 ms/op
     p(99.9000) =     34.884 ms/op
     p(99.9900) =     43.713 ms/op
     p(99.9990) =     43.713 ms/op
     p(99.9999) =     43.713 ms/op
    p(100.0000) =     43.713 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:16
# Fork: 1 of 1
# Warmup Iteration   1: 11.579 ±(99.9%) 0.409 ms/op
Iteration   1: 6.360 ±(99.9%) 0.164 ms/op
                 getUser·p0.00:   1.862 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   8.679 ms/op
                 getUser·p0.95:   12.261 ms/op
                 getUser·p0.99:   27.262 ms/op
                 getUser·p0.999:  37.943 ms/op
                 getUser·p0.9999: 38.207 ms/op
                 getUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5012
  mean =      6.360 ±(99.9%) 0.164 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 1210 
    [ 5.000,  7.500) = 3068 
    [ 7.500, 10.000) = 355 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.862 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      8.679 ms/op
     p(95.0000) =     12.261 ms/op
     p(99.0000) =     27.262 ms/op
     p(99.9000) =     37.943 ms/op
     p(99.9900) =     38.207 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:08
# Fork: 1 of 1
# Warmup Iteration   1: 30.866 ±(99.9%) 1.503 ms/op
Iteration   1: 19.815 ±(99.9%) 0.399 ms/op
                 listUser·p0.00:   5.980 ms/op
                 listUser·p0.50:   19.759 ms/op
                 listUser·p0.90:   25.605 ms/op
                 listUser·p0.95:   28.377 ms/op
                 listUser·p0.99:   32.646 ms/op
                 listUser·p0.999:  40.661 ms/op
                 listUser·p0.9999: 41.026 ms/op
                 listUser·p1.00:   41.026 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1617
  mean =     19.815 ±(99.9%) 0.399 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 22 
    [10.000, 15.000) = 263 
    [15.000, 20.000) = 556 
    [20.000, 25.000) = 573 
    [25.000, 30.000) = 160 
    [30.000, 35.000) = 37 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      5.980 ms/op
     p(50.0000) =     19.759 ms/op
     p(90.0000) =     25.605 ms/op
     p(95.0000) =     28.377 ms/op
     p(99.0000) =     32.646 ms/op
     p(99.9000) =     40.661 ms/op
     p(99.9900) =     41.026 ms/op
     p(99.9990) =     41.026 ms/op
     p(99.9999) =     41.026 ms/op
    p(100.0000) =     41.026 ms/op


# Run complete. Total time: 00:01:36

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.794          ops/ms
Client.existUser                       thrpt         7.301          ops/ms
Client.getUser                         thrpt         5.240          ops/ms
Client.listUser                        thrpt         1.100          ops/ms
Client.createUser                       avgt         8.656           ms/op
Client.existUser                        avgt         4.276           ms/op
Client.getUser                          avgt         5.466           ms/op
Client.listUser                         avgt        23.478           ms/op
Client.createUser                     sample  4299   7.380 ± 0.259   ms/op
Client.createUser:createUser·p0.00    sample         1.841           ms/op
Client.createUser:createUser·p0.50    sample         6.152           ms/op
Client.createUser:createUser·p0.90    sample        12.567           ms/op
Client.createUser:createUser·p0.95    sample        14.959           ms/op
Client.createUser:createUser·p0.99    sample        31.228           ms/op
Client.createUser:createUser·p0.999   sample        49.657           ms/op
Client.createUser:createUser·p0.9999  sample        50.070           ms/op
Client.createUser:createUser·p1.00    sample        50.070           ms/op
Client.existUser                      sample  9791   3.238 ± 0.094   ms/op
Client.existUser:existUser·p0.00      sample         1.008           ms/op
Client.existUser:existUser·p0.50      sample         2.404           ms/op
Client.existUser:existUser·p0.90      sample         4.645           ms/op
Client.existUser:existUser·p0.95      sample         8.585           ms/op
Client.existUser:existUser·p0.99      sample        14.452           ms/op
Client.existUser:existUser·p0.999     sample        34.884           ms/op
Client.existUser:existUser·p0.9999    sample        43.713           ms/op
Client.existUser:existUser·p1.00      sample        43.713           ms/op
Client.getUser                        sample  5012   6.360 ± 0.164   ms/op
Client.getUser:getUser·p0.00          sample         1.862           ms/op
Client.getUser:getUser·p0.50          sample         5.423           ms/op
Client.getUser:getUser·p0.90          sample         8.679           ms/op
Client.getUser:getUser·p0.95          sample        12.261           ms/op
Client.getUser:getUser·p0.99          sample        27.262           ms/op
Client.getUser:getUser·p0.999         sample        37.943           ms/op
Client.getUser:getUser·p0.9999        sample        38.207           ms/op
Client.getUser:getUser·p1.00          sample        38.207           ms/op
Client.listUser                       sample  1617  19.815 ± 0.399   ms/op
Client.listUser:listUser·p0.00        sample         5.980           ms/op
Client.listUser:listUser·p0.50        sample        19.759           ms/op
Client.listUser:listUser·p0.90        sample        25.605           ms/op
Client.listUser:listUser·p0.95        sample        28.377           ms/op
Client.listUser:listUser·p0.99        sample        32.646           ms/op
Client.listUser:listUser·p0.999       sample        40.661           ms/op
Client.listUser:listUser·p0.9999      sample        41.026           ms/op
Client.listUser:listUser·p1.00        sample        41.026           ms/op
