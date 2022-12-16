# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.733 ops/ms
Iteration   1: 2.520 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.520 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.486 ops/ms
Iteration   1: 7.353 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.353 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.679 ops/ms
Iteration   1: 5.040 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.040 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.836 ops/ms
Iteration   1: 1.386 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.386 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 15.188 ±(99.9%) 0.214 ms/op
Iteration   1: 6.647 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.647 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.465 ±(99.9%) 0.077 ms/op
Iteration   1: 3.855 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.855 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.516 ±(99.9%) 0.096 ms/op
Iteration   1: 4.664 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 25.547 ±(99.9%) 0.332 ms/op
Iteration   1: 17.645 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.645 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.955 ±(99.9%) 0.249 ms/op
Iteration   1: 5.674 ±(99.9%) 0.078 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   5.571 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   6.733 ms/op
                 createUser·p0.99:   15.024 ms/op
                 createUser·p0.999:  17.737 ms/op
                 createUser·p0.9999: 18.022 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5641
  mean =      5.674 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 289 
    [ 2.500,  3.750) = 148 
    [ 3.750,  5.000) = 484 
    [ 5.000,  6.250) = 4099 
    [ 6.250,  7.500) = 382 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.577 ms/op
     p(50.0000) =      5.571 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      6.733 ms/op
     p(99.0000) =     15.024 ms/op
     p(99.9000) =     17.737 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.271 ±(99.9%) 0.212 ms/op
Iteration   1: 3.748 ±(99.9%) 0.086 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   3.465 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   5.857 ms/op
                 existUser·p0.99:   15.174 ms/op
                 existUser·p0.999:  29.243 ms/op
                 existUser·p0.9999: 30.933 ms/op
                 existUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8570
  mean =      3.748 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 815 
    [ 2.500,  5.000) = 7284 
    [ 5.000,  7.500) = 107 
    [ 7.500, 10.000) = 188 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =     15.174 ms/op
     p(99.9000) =     29.243 ms/op
     p(99.9900) =     30.933 ms/op
     p(99.9990) =     30.933 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 8.591 ±(99.9%) 0.266 ms/op
Iteration   1: 4.880 ±(99.9%) 0.053 ms/op
                 getUser·p0.00:   1.962 ms/op
                 getUser·p0.50:   4.874 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   6.291 ms/op
                 getUser·p0.99:   9.550 ms/op
                 getUser·p0.999:  15.359 ms/op
                 getUser·p0.9999: 19.661 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6551
  mean =      4.880 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 24 
    [ 2.500,  3.750) = 940 
    [ 3.750,  5.000) = 2626 
    [ 5.000,  6.250) = 2592 
    [ 6.250,  7.500) = 297 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.962 ms/op
     p(50.0000) =      4.874 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      6.291 ms/op
     p(99.0000) =      9.550 ms/op
     p(99.9000) =     15.359 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.506 ±(99.9%) 0.682 ms/op
Iteration   1: 15.657 ±(99.9%) 0.288 ms/op
                 listUser·p0.00:   7.610 ms/op
                 listUser·p0.50:   13.844 ms/op
                 listUser·p0.90:   21.201 ms/op
                 listUser·p0.95:   23.518 ms/op
                 listUser·p0.99:   32.694 ms/op
                 listUser·p0.999:  35.843 ms/op
                 listUser·p0.9999: 35.914 ms/op
                 listUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2041
  mean =     15.657 ±(99.9%) 0.288 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 1324 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 224 
    [20.000, 22.500) = 167 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      7.610 ms/op
     p(50.0000) =     13.844 ms/op
     p(90.0000) =     21.201 ms/op
     p(95.0000) =     23.518 ms/op
     p(99.0000) =     32.694 ms/op
     p(99.9000) =     35.843 ms/op
     p(99.9900) =     35.914 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.520          ops/ms
Client.existUser                       thrpt         7.353          ops/ms
Client.getUser                         thrpt         5.040          ops/ms
Client.listUser                        thrpt         1.386          ops/ms
Client.createUser                       avgt         6.647           ms/op
Client.existUser                        avgt         3.855           ms/op
Client.getUser                          avgt         4.664           ms/op
Client.listUser                         avgt        17.645           ms/op
Client.createUser                     sample  5641   5.674 ± 0.078   ms/op
Client.createUser:createUser·p0.00    sample         1.577           ms/op
Client.createUser:createUser·p0.50    sample         5.571           ms/op
Client.createUser:createUser·p0.90    sample         6.267           ms/op
Client.createUser:createUser·p0.95    sample         6.733           ms/op
Client.createUser:createUser·p0.99    sample        15.024           ms/op
Client.createUser:createUser·p0.999   sample        17.737           ms/op
Client.createUser:createUser·p0.9999  sample        18.022           ms/op
Client.createUser:createUser·p1.00    sample        18.022           ms/op
Client.existUser                      sample  8570   3.748 ± 0.086   ms/op
Client.existUser:existUser·p0.00      sample         0.669           ms/op
Client.existUser:existUser·p0.50      sample         3.465           ms/op
Client.existUser:existUser·p0.90      sample         3.916           ms/op
Client.existUser:existUser·p0.95      sample         5.857           ms/op
Client.existUser:existUser·p0.99      sample        15.174           ms/op
Client.existUser:existUser·p0.999     sample        29.243           ms/op
Client.existUser:existUser·p0.9999    sample        30.933           ms/op
Client.existUser:existUser·p1.00      sample        30.933           ms/op
Client.getUser                        sample  6551   4.880 ± 0.053   ms/op
Client.getUser:getUser·p0.00          sample         1.962           ms/op
Client.getUser:getUser·p0.50          sample         4.874           ms/op
Client.getUser:getUser·p0.90          sample         5.931           ms/op
Client.getUser:getUser·p0.95          sample         6.291           ms/op
Client.getUser:getUser·p0.99          sample         9.550           ms/op
Client.getUser:getUser·p0.999         sample        15.359           ms/op
Client.getUser:getUser·p0.9999        sample        19.661           ms/op
Client.getUser:getUser·p1.00          sample        19.661           ms/op
Client.listUser                       sample  2041  15.657 ± 0.288   ms/op
Client.listUser:listUser·p0.00        sample         7.610           ms/op
Client.listUser:listUser·p0.50        sample        13.844           ms/op
Client.listUser:listUser·p0.90        sample        21.201           ms/op
Client.listUser:listUser·p0.95        sample        23.518           ms/op
Client.listUser:listUser·p0.99        sample        32.694           ms/op
Client.listUser:listUser·p0.999       sample        35.843           ms/op
Client.listUser:listUser·p0.9999      sample        35.914           ms/op
Client.listUser:listUser·p1.00        sample        35.914           ms/op
