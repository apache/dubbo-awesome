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
# Warmup Iteration   1: 2.346 ops/ms
Iteration   1: 6.384 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.384 ops/ms


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
# Warmup Iteration   1: 6.614 ops/ms
Iteration   1: 13.545 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.545 ops/ms


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
# Warmup Iteration   1: 4.794 ops/ms
Iteration   1: 9.250 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.250 ops/ms


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
# Warmup Iteration   1: 2.120 ops/ms
Iteration   1: 3.447 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.447 ops/ms


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
# Warmup Iteration   1: 5.241 ±(99.9%) 0.117 ms/op
Iteration   1: 3.043 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.043 ms/op


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
# Warmup Iteration   1: 3.034 ±(99.9%) 0.036 ms/op
Iteration   1: 1.646 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.646 ms/op


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
# Warmup Iteration   1: 4.451 ±(99.9%) 0.059 ms/op
Iteration   1: 2.928 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.928 ms/op


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
# Warmup Iteration   1: 13.183 ±(99.9%) 0.240 ms/op
Iteration   1: 9.418 ±(99.9%) 0.233 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.418 ms/op


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
# Warmup Iteration   1: 4.956 ±(99.9%) 0.097 ms/op
Iteration   1: 3.016 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   2.728 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.204 ms/op
                 createUser·p0.99:   11.928 ms/op
                 createUser·p0.999:  17.806 ms/op
                 createUser·p0.9999: 19.745 ms/op
                 createUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10596
  mean =      3.016 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 2934 
    [ 2.500,  3.750) = 6487 
    [ 3.750,  5.000) = 892 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      2.728 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.204 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     17.806 ms/op
     p(99.9900) =     19.745 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 3.117 ±(99.9%) 0.072 ms/op
Iteration   1: 1.728 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   1.677 ms/op
                 existUser·p0.90:   2.331 ms/op
                 existUser·p0.95:   2.545 ms/op
                 existUser·p0.99:   3.146 ms/op
                 existUser·p0.999:  12.491 ms/op
                 existUser·p0.9999: 12.618 ms/op
                 existUser·p1.00:   12.632 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18534
  mean =      1.728 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3377 
    [ 1.250,  2.500) = 14119 
    [ 2.500,  3.750) = 930 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      1.677 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.545 ms/op
     p(99.0000) =      3.146 ms/op
     p(99.9000) =     12.491 ms/op
     p(99.9900) =     12.618 ms/op
     p(99.9990) =     12.632 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


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
# Warmup Iteration   1: 4.368 ±(99.9%) 0.100 ms/op
Iteration   1: 2.849 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.377 ms/op
                 getUser·p0.50:   2.785 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  11.715 ms/op
                 getUser·p0.9999: 12.931 ms/op
                 getUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11221
  mean =      2.849 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 3720 
    [ 2.500,  3.750) = 6516 
    [ 3.750,  5.000) = 857 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.377 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =     11.715 ms/op
     p(99.9900) =     12.931 ms/op
     p(99.9990) =     12.943 ms/op
     p(99.9999) =     12.943 ms/op
    p(100.0000) =     12.943 ms/op


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
# Warmup Iteration   1: 11.131 ±(99.9%) 0.395 ms/op
Iteration   1: 8.403 ±(99.9%) 0.109 ms/op
                 listUser·p0.00:   2.806 ms/op
                 listUser·p0.50:   8.159 ms/op
                 listUser·p0.90:   11.026 ms/op
                 listUser·p0.95:   11.862 ms/op
                 listUser·p0.99:   13.850 ms/op
                 listUser·p0.999:  17.465 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3833
  mean =      8.403 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 14 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 418 
    [ 6.250,  7.500) = 898 
    [ 7.500,  8.750) = 898 
    [ 8.750, 10.000) = 638 
    [10.000, 11.250) = 568 
    [11.250, 12.500) = 179 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.806 ms/op
     p(50.0000) =      8.159 ms/op
     p(90.0000) =     11.026 ms/op
     p(95.0000) =     11.862 ms/op
     p(99.0000) =     13.850 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.384          ops/ms
Client.existUser                       thrpt         13.545          ops/ms
Client.getUser                         thrpt          9.250          ops/ms
Client.listUser                        thrpt          3.447          ops/ms
Client.createUser                       avgt          3.043           ms/op
Client.existUser                        avgt          1.646           ms/op
Client.getUser                          avgt          2.928           ms/op
Client.listUser                         avgt          9.418           ms/op
Client.createUser                     sample  10596   3.016 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample          1.143           ms/op
Client.createUser:createUser·p0.50    sample          2.728           ms/op
Client.createUser:createUser·p0.90    sample          3.826           ms/op
Client.createUser:createUser·p0.95    sample          4.204           ms/op
Client.createUser:createUser·p0.99    sample         11.928           ms/op
Client.createUser:createUser·p0.999   sample         17.806           ms/op
Client.createUser:createUser·p0.9999  sample         19.745           ms/op
Client.createUser:createUser·p1.00    sample         19.759           ms/op
Client.existUser                      sample  18534   1.728 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.686           ms/op
Client.existUser:existUser·p0.50      sample          1.677           ms/op
Client.existUser:existUser·p0.90      sample          2.331           ms/op
Client.existUser:existUser·p0.95      sample          2.545           ms/op
Client.existUser:existUser·p0.99      sample          3.146           ms/op
Client.existUser:existUser·p0.999     sample         12.491           ms/op
Client.existUser:existUser·p0.9999    sample         12.618           ms/op
Client.existUser:existUser·p1.00      sample         12.632           ms/op
Client.getUser                        sample  11221   2.849 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.377           ms/op
Client.getUser:getUser·p0.50          sample          2.785           ms/op
Client.getUser:getUser·p0.90          sample          3.674           ms/op
Client.getUser:getUser·p0.95          sample          3.953           ms/op
Client.getUser:getUser·p0.99          sample          4.956           ms/op
Client.getUser:getUser·p0.999         sample         11.715           ms/op
Client.getUser:getUser·p0.9999        sample         12.931           ms/op
Client.getUser:getUser·p1.00          sample         12.943           ms/op
Client.listUser                       sample   3833   8.403 ± 0.109   ms/op
Client.listUser:listUser·p0.00        sample          2.806           ms/op
Client.listUser:listUser·p0.50        sample          8.159           ms/op
Client.listUser:listUser·p0.90        sample         11.026           ms/op
Client.listUser:listUser·p0.95        sample         11.862           ms/op
Client.listUser:listUser·p0.99        sample         13.850           ms/op
Client.listUser:listUser·p0.999       sample         17.465           ms/op
Client.listUser:listUser·p0.9999      sample         18.022           ms/op
Client.listUser:listUser·p1.00        sample         18.022           ms/op
