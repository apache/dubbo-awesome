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
# Warmup Iteration   1: 2.567 ops/ms
Iteration   1: 6.016 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.016 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.083 ops/ms
Iteration   1: 12.375 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.375 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.851 ops/ms
Iteration   1: 9.258 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.258 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.299 ops/ms
Iteration   1: 3.660 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.660 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.205 ±(99.9%) 0.065 ms/op
Iteration   1: 2.968 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.968 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.539 ±(99.9%) 0.034 ms/op
Iteration   1: 2.072 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.072 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ±(99.9%) 0.049 ms/op
Iteration   1: 2.943 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.943 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.998 ±(99.9%) 0.315 ms/op
Iteration   1: 9.615 ±(99.9%) 0.151 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.615 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.037 ±(99.9%) 0.120 ms/op
Iteration   1: 3.200 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   9.200 ms/op
                 createUser·p0.999:  26.083 ms/op
                 createUser·p0.9999: 26.771 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9982
  mean =      3.200 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2055 
    [ 2.500,  5.000) = 7669 
    [ 5.000,  7.500) = 79 
    [ 7.500, 10.000) = 83 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      9.200 ms/op
     p(99.9000) =     26.083 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.906 ±(99.9%) 0.057 ms/op
Iteration   1: 1.858 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.277 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   2.851 ms/op
                 existUser·p0.999:  5.675 ms/op
                 existUser·p0.9999: 6.289 ms/op
                 existUser·p1.00:   6.324 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17236
  mean =      1.858 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 802 
    [1.500, 2.000) = 12627 
    [2.000, 2.500) = 2943 
    [2.500, 3.000) = 733 
    [3.000, 3.500) = 57 
    [3.500, 4.000) = 4 
    [4.000, 4.500) = 0 
    [4.500, 5.000) = 15 
    [5.000, 5.500) = 30 
    [5.500, 6.000) = 12 
    [6.000, 6.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      2.851 ms/op
     p(99.9000) =      5.675 ms/op
     p(99.9900) =      6.289 ms/op
     p(99.9990) =      6.324 ms/op
     p(99.9999) =      6.324 ms/op
    p(100.0000) =      6.324 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.209 ±(99.9%) 0.094 ms/op
Iteration   1: 3.097 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   2.904 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.217 ms/op
                 getUser·p0.999:  25.474 ms/op
                 getUser·p0.9999: 28.770 ms/op
                 getUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10327
  mean =      3.097 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3079 
    [ 2.500,  5.000) = 6915 
    [ 5.000,  7.500) = 297 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.217 ms/op
     p(99.9000) =     25.474 ms/op
     p(99.9900) =     28.770 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.126 ±(99.9%) 0.378 ms/op
Iteration   1: 7.537 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   2.904 ms/op
                 listUser·p0.50:   7.168 ms/op
                 listUser·p0.90:   9.866 ms/op
                 listUser·p0.95:   11.077 ms/op
                 listUser·p0.99:   19.497 ms/op
                 listUser·p0.999:  22.796 ms/op
                 listUser·p0.9999: 23.658 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4257
  mean =      7.537 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 198 
    [ 5.000,  7.500) = 2325 
    [ 7.500, 10.000) = 1337 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.904 ms/op
     p(50.0000) =      7.168 ms/op
     p(90.0000) =      9.866 ms/op
     p(95.0000) =     11.077 ms/op
     p(99.0000) =     19.497 ms/op
     p(99.9000) =     22.796 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.016          ops/ms
Client.existUser                       thrpt         12.375          ops/ms
Client.getUser                         thrpt          9.258          ops/ms
Client.listUser                        thrpt          3.660          ops/ms
Client.createUser                       avgt          2.968           ms/op
Client.existUser                        avgt          2.072           ms/op
Client.getUser                          avgt          2.943           ms/op
Client.listUser                         avgt          9.615           ms/op
Client.createUser                     sample   9982   3.200 ± 0.057   ms/op
Client.createUser:createUser·p0.00    sample          1.161           ms/op
Client.createUser:createUser·p0.50    sample          2.941           ms/op
Client.createUser:createUser·p0.90    sample          3.875           ms/op
Client.createUser:createUser·p0.95    sample          4.325           ms/op
Client.createUser:createUser·p0.99    sample          9.200           ms/op
Client.createUser:createUser·p0.999   sample         26.083           ms/op
Client.createUser:createUser·p0.9999  sample         26.771           ms/op
Client.createUser:createUser·p1.00    sample         26.771           ms/op
Client.existUser                      sample  17236   1.858 ± 0.009   ms/op
Client.existUser:existUser·p0.00      sample          0.848           ms/op
Client.existUser:existUser·p0.50      sample          1.769           ms/op
Client.existUser:existUser·p0.90      sample          2.277           ms/op
Client.existUser:existUser·p0.95      sample          2.499           ms/op
Client.existUser:existUser·p0.99      sample          2.851           ms/op
Client.existUser:existUser·p0.999     sample          5.675           ms/op
Client.existUser:existUser·p0.9999    sample          6.289           ms/op
Client.existUser:existUser·p1.00      sample          6.324           ms/op
Client.getUser                        sample  10327   3.097 ± 0.049   ms/op
Client.getUser:getUser·p0.00          sample          0.826           ms/op
Client.getUser:getUser·p0.50          sample          2.904           ms/op
Client.getUser:getUser·p0.90          sample          4.030           ms/op
Client.getUser:getUser·p0.95          sample          4.522           ms/op
Client.getUser:getUser·p0.99          sample          6.217           ms/op
Client.getUser:getUser·p0.999         sample         25.474           ms/op
Client.getUser:getUser·p0.9999        sample         28.770           ms/op
Client.getUser:getUser·p1.00          sample         28.770           ms/op
Client.listUser                       sample   4257   7.537 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          2.904           ms/op
Client.listUser:listUser·p0.50        sample          7.168           ms/op
Client.listUser:listUser·p0.90        sample          9.866           ms/op
Client.listUser:listUser·p0.95        sample         11.077           ms/op
Client.listUser:listUser·p0.99        sample         19.497           ms/op
Client.listUser:listUser·p0.999       sample         22.796           ms/op
Client.listUser:listUser·p0.9999      sample         23.658           ms/op
Client.listUser:listUser·p1.00        sample         23.658           ms/op
