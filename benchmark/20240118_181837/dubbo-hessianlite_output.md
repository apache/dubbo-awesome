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
# Warmup Iteration   1: 2.360 ops/ms
Iteration   1: 6.121 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.121 ops/ms


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
# Warmup Iteration   1: 5.829 ops/ms
Iteration   1: 10.769 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.769 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.100 ops/ms
Iteration   1: 7.945 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.945 ops/ms


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
# Warmup Iteration   1: 2.159 ops/ms
Iteration   1: 3.323 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.323 ops/ms


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
# Warmup Iteration   1: 5.421 ±(99.9%) 0.069 ms/op
Iteration   1: 3.324 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.324 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.035 ms/op
Iteration   1: 1.839 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.839 ms/op


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
# Warmup Iteration   1: 4.598 ±(99.9%) 0.065 ms/op
Iteration   1: 3.097 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.097 ms/op


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
# Warmup Iteration   1: 10.855 ±(99.9%) 0.194 ms/op
Iteration   1: 9.323 ±(99.9%) 0.114 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.323 ms/op


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
# Warmup Iteration   1: 5.018 ±(99.9%) 0.099 ms/op
Iteration   1: 3.157 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   4.080 ms/op
                 createUser·p0.99:   8.569 ms/op
                 createUser·p0.999:  20.534 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10116
  mean =      3.157 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 601 
    [ 2.500,  5.000) = 9240 
    [ 5.000,  7.500) = 147 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     20.534 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     20.840 ms/op
     p(99.9999) =     20.840 ms/op
    p(100.0000) =     20.840 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.086 ms/op
Iteration   1: 1.884 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.224 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   3.486 ms/op
                 existUser·p0.999:  7.618 ms/op
                 existUser·p0.9999: 8.474 ms/op
                 existUser·p1.00:   8.520 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17010
  mean =      1.884 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 779 
    [1.500, 2.000) = 12518 
    [2.000, 2.500) = 2946 
    [2.500, 3.000) = 522 
    [3.000, 3.500) = 80 
    [3.500, 4.000) = 51 
    [4.000, 4.500) = 33 
    [4.500, 5.000) = 10 
    [5.000, 5.500) = 3 
    [5.500, 6.000) = 25 
    [6.000, 6.500) = 11 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 26 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =      7.618 ms/op
     p(99.9900) =      8.474 ms/op
     p(99.9990) =      8.520 ms/op
     p(99.9999) =      8.520 ms/op
    p(100.0000) =      8.520 ms/op


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
# Warmup Iteration   1: 4.641 ±(99.9%) 0.106 ms/op
Iteration   1: 2.827 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   2.646 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  10.255 ms/op
                 getUser·p0.9999: 11.985 ms/op
                 getUser·p1.00:   12.075 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11301
  mean =      2.827 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 19 
    [ 1.250,  2.500) = 4788 
    [ 2.500,  3.750) = 5555 
    [ 3.750,  5.000) = 820 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =     10.255 ms/op
     p(99.9900) =     11.985 ms/op
     p(99.9990) =     12.075 ms/op
     p(99.9999) =     12.075 ms/op
    p(100.0000) =     12.075 ms/op


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
# Warmup Iteration   1: 12.874 ±(99.9%) 0.432 ms/op
Iteration   1: 7.564 ±(99.9%) 0.118 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   7.135 ms/op
                 listUser·p0.90:   9.470 ms/op
                 listUser·p0.95:   11.080 ms/op
                 listUser·p0.99:   18.378 ms/op
                 listUser·p0.999:  21.999 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   23.298 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4213
  mean =      7.564 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 192 
    [ 5.000,  7.500) = 2310 
    [ 7.500, 10.000) = 1388 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.130 ms/op
     p(50.0000) =      7.135 ms/op
     p(90.0000) =      9.470 ms/op
     p(95.0000) =     11.080 ms/op
     p(99.0000) =     18.378 ms/op
     p(99.9000) =     21.999 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     23.298 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.121          ops/ms
Client.existUser                       thrpt         10.769          ops/ms
Client.getUser                         thrpt          7.945          ops/ms
Client.listUser                        thrpt          3.323          ops/ms
Client.createUser                       avgt          3.324           ms/op
Client.existUser                        avgt          1.839           ms/op
Client.getUser                          avgt          3.097           ms/op
Client.listUser                         avgt          9.323           ms/op
Client.createUser                     sample  10116   3.157 ± 0.047   ms/op
Client.createUser:createUser·p0.00    sample          1.182           ms/op
Client.createUser:createUser·p0.50    sample          2.912           ms/op
Client.createUser:createUser·p0.90    sample          3.617           ms/op
Client.createUser:createUser·p0.95    sample          4.080           ms/op
Client.createUser:createUser·p0.99    sample          8.569           ms/op
Client.createUser:createUser·p0.999   sample         20.534           ms/op
Client.createUser:createUser·p0.9999  sample         20.840           ms/op
Client.createUser:createUser·p1.00    sample         20.840           ms/op
Client.existUser                      sample  17010   1.884 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          1.051           ms/op
Client.existUser:existUser·p0.50      sample          1.804           ms/op
Client.existUser:existUser·p0.90      sample          2.224           ms/op
Client.existUser:existUser·p0.95      sample          2.458           ms/op
Client.existUser:existUser·p0.99      sample          3.486           ms/op
Client.existUser:existUser·p0.999     sample          7.618           ms/op
Client.existUser:existUser·p0.9999    sample          8.474           ms/op
Client.existUser:existUser·p1.00      sample          8.520           ms/op
Client.getUser                        sample  11301   2.827 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.738           ms/op
Client.getUser:getUser·p0.50          sample          2.646           ms/op
Client.getUser:getUser·p0.90          sample          3.695           ms/op
Client.getUser:getUser·p0.95          sample          3.969           ms/op
Client.getUser:getUser·p0.99          sample          5.046           ms/op
Client.getUser:getUser·p0.999         sample         10.255           ms/op
Client.getUser:getUser·p0.9999        sample         11.985           ms/op
Client.getUser:getUser·p1.00          sample         12.075           ms/op
Client.listUser                       sample   4213   7.564 ± 0.118   ms/op
Client.listUser:listUser·p0.00        sample          2.130           ms/op
Client.listUser:listUser·p0.50        sample          7.135           ms/op
Client.listUser:listUser·p0.90        sample          9.470           ms/op
Client.listUser:listUser·p0.95        sample         11.080           ms/op
Client.listUser:listUser·p0.99        sample         18.378           ms/op
Client.listUser:listUser·p0.999       sample         21.999           ms/op
Client.listUser:listUser·p0.9999      sample         23.298           ms/op
Client.listUser:listUser·p1.00        sample         23.298           ms/op
