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
# Warmup Iteration   1: 0.852 ops/ms
Iteration   1: 2.007 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.007 ops/ms


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
# Warmup Iteration   1: 2.388 ops/ms
Iteration   1: 3.978 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.978 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.775 ops/ms
Iteration   1: 3.555 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.555 ops/ms


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
# Warmup Iteration   1: 0.696 ops/ms
Iteration   1: 1.162 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.162 ops/ms


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
# Warmup Iteration   1: 25.045 ±(99.9%) 0.280 ms/op
Iteration   1: 10.077 ±(99.9%) 0.047 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  10.077 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.853 ±(99.9%) 0.206 ms/op
Iteration   1: 5.480 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.480 ms/op


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
# Warmup Iteration   1: 13.200 ±(99.9%) 0.172 ms/op
Iteration   1: 5.561 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.561 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 37.400 ±(99.9%) 0.789 ms/op
Iteration   1: 23.450 ±(99.9%) 0.148 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  23.450 ms/op


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
# Warmup Iteration   1: 16.315 ±(99.9%) 0.661 ms/op
Iteration   1: 8.053 ±(99.9%) 0.209 ms/op
                 createUser·p0.00:   3.228 ms/op
                 createUser·p0.50:   7.602 ms/op
                 createUser·p0.90:   9.829 ms/op
                 createUser·p0.95:   15.057 ms/op
                 createUser·p0.99:   21.234 ms/op
                 createUser·p0.999:  42.991 ms/op
                 createUser·p0.9999: 43.319 ms/op
                 createUser·p1.00:   43.319 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4016
  mean =      8.053 ±(99.9%) 0.209 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 563 
    [ 5.000, 10.000) = 3063 
    [10.000, 15.000) = 179 
    [15.000, 20.000) = 156 
    [20.000, 25.000) = 23 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      3.228 ms/op
     p(50.0000) =      7.602 ms/op
     p(90.0000) =      9.829 ms/op
     p(95.0000) =     15.057 ms/op
     p(99.0000) =     21.234 ms/op
     p(99.9000) =     42.991 ms/op
     p(99.9900) =     43.319 ms/op
     p(99.9990) =     43.319 ms/op
     p(99.9999) =     43.319 ms/op
    p(100.0000) =     43.319 ms/op


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
# Warmup Iteration   1: 8.054 ±(99.9%) 0.309 ms/op
Iteration   1: 5.383 ±(99.9%) 0.111 ms/op
                 existUser·p0.00:   0.582 ms/op
                 existUser·p0.50:   5.407 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   8.880 ms/op
                 existUser·p0.99:   20.093 ms/op
                 existUser·p0.999:  29.361 ms/op
                 existUser·p0.9999: 30.212 ms/op
                 existUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 5979
  mean =      5.383 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 2118 
    [ 5.000,  7.500) = 3361 
    [ 7.500, 10.000) = 186 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.582 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      6.111 ms/op
     p(95.0000) =      8.880 ms/op
     p(99.0000) =     20.093 ms/op
     p(99.9000) =     29.361 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     30.212 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 12.693 ±(99.9%) 0.404 ms/op
Iteration   1: 5.746 ±(99.9%) 0.121 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   5.206 ms/op
                 getUser·p0.90:   7.539 ms/op
                 getUser·p0.95:   8.819 ms/op
                 getUser·p0.99:   22.621 ms/op
                 getUser·p0.999:  26.673 ms/op
                 getUser·p0.9999: 26.673 ms/op
                 getUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5566
  mean =      5.746 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 2573 
    [ 5.000,  7.500) = 2409 
    [ 7.500, 10.000) = 390 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      5.206 ms/op
     p(90.0000) =      7.539 ms/op
     p(95.0000) =      8.819 ms/op
     p(99.0000) =     22.621 ms/op
     p(99.9000) =     26.673 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     26.673 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 33.534 ±(99.9%) 1.246 ms/op
Iteration   1: 22.164 ±(99.9%) 0.584 ms/op
                 listUser·p0.00:   4.342 ms/op
                 listUser·p0.50:   21.758 ms/op
                 listUser·p0.90:   27.591 ms/op
                 listUser·p0.95:   34.659 ms/op
                 listUser·p0.99:   45.399 ms/op
                 listUser·p0.999:  56.479 ms/op
                 listUser·p0.9999: 57.541 ms/op
                 listUser·p1.00:   57.541 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1462
  mean =     22.164 ±(99.9%) 0.584 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1 
    [ 5.000, 10.000) = 10 
    [10.000, 15.000) = 176 
    [15.000, 20.000) = 317 
    [20.000, 25.000) = 510 
    [25.000, 30.000) = 353 
    [30.000, 35.000) = 24 
    [35.000, 40.000) = 40 
    [40.000, 45.000) = 15 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      4.342 ms/op
     p(50.0000) =     21.758 ms/op
     p(90.0000) =     27.591 ms/op
     p(95.0000) =     34.659 ms/op
     p(99.0000) =     45.399 ms/op
     p(99.9000) =     56.479 ms/op
     p(99.9900) =     57.541 ms/op
     p(99.9990) =     57.541 ms/op
     p(99.9999) =     57.541 ms/op
    p(100.0000) =     57.541 ms/op


# Run complete. Total time: 00:01:29

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.007          ops/ms
Client.existUser                       thrpt         3.978          ops/ms
Client.getUser                         thrpt         3.555          ops/ms
Client.listUser                        thrpt         1.162          ops/ms
Client.createUser                       avgt        10.077           ms/op
Client.existUser                        avgt         5.480           ms/op
Client.getUser                          avgt         5.561           ms/op
Client.listUser                         avgt        23.450           ms/op
Client.createUser                     sample  4016   8.053 ± 0.209   ms/op
Client.createUser:createUser·p0.00    sample         3.228           ms/op
Client.createUser:createUser·p0.50    sample         7.602           ms/op
Client.createUser:createUser·p0.90    sample         9.829           ms/op
Client.createUser:createUser·p0.95    sample        15.057           ms/op
Client.createUser:createUser·p0.99    sample        21.234           ms/op
Client.createUser:createUser·p0.999   sample        42.991           ms/op
Client.createUser:createUser·p0.9999  sample        43.319           ms/op
Client.createUser:createUser·p1.00    sample        43.319           ms/op
Client.existUser                      sample  5979   5.383 ± 0.111   ms/op
Client.existUser:existUser·p0.00      sample         0.582           ms/op
Client.existUser:existUser·p0.50      sample         5.407           ms/op
Client.existUser:existUser·p0.90      sample         6.111           ms/op
Client.existUser:existUser·p0.95      sample         8.880           ms/op
Client.existUser:existUser·p0.99      sample        20.093           ms/op
Client.existUser:existUser·p0.999     sample        29.361           ms/op
Client.existUser:existUser·p0.9999    sample        30.212           ms/op
Client.existUser:existUser·p1.00      sample        30.212           ms/op
Client.getUser                        sample  5566   5.746 ± 0.121   ms/op
Client.getUser:getUser·p0.00          sample         1.174           ms/op
Client.getUser:getUser·p0.50          sample         5.206           ms/op
Client.getUser:getUser·p0.90          sample         7.539           ms/op
Client.getUser:getUser·p0.95          sample         8.819           ms/op
Client.getUser:getUser·p0.99          sample        22.621           ms/op
Client.getUser:getUser·p0.999         sample        26.673           ms/op
Client.getUser:getUser·p0.9999        sample        26.673           ms/op
Client.getUser:getUser·p1.00          sample        26.673           ms/op
Client.listUser                       sample  1462  22.164 ± 0.584   ms/op
Client.listUser:listUser·p0.00        sample         4.342           ms/op
Client.listUser:listUser·p0.50        sample        21.758           ms/op
Client.listUser:listUser·p0.90        sample        27.591           ms/op
Client.listUser:listUser·p0.95        sample        34.659           ms/op
Client.listUser:listUser·p0.99        sample        45.399           ms/op
Client.listUser:listUser·p0.999       sample        56.479           ms/op
Client.listUser:listUser·p0.9999      sample        57.541           ms/op
Client.listUser:listUser·p1.00        sample        57.541           ms/op
