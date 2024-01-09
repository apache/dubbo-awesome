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
# Warmup Iteration   1: 2.130 ops/ms
Iteration   1: 5.963 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.963 ops/ms


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
# Warmup Iteration   1: 6.099 ops/ms
Iteration   1: 12.135 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.135 ops/ms


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
# Warmup Iteration   1: 3.774 ops/ms
Iteration   1: 7.903 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.903 ops/ms


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
# Warmup Iteration   1: 2.055 ops/ms
Iteration   1: 3.485 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.485 ops/ms


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
# Warmup Iteration   1: 5.597 ±(99.9%) 0.084 ms/op
Iteration   1: 3.133 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.133 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.043 ms/op
Iteration   1: 1.899 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.899 ms/op


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
# Warmup Iteration   1: 5.031 ±(99.9%) 0.057 ms/op
Iteration   1: 3.206 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.206 ms/op


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
# Warmup Iteration   1: 14.360 ±(99.9%) 0.326 ms/op
Iteration   1: 9.971 ±(99.9%) 0.135 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.971 ms/op


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
# Warmup Iteration   1: 5.011 ±(99.9%) 0.142 ms/op
Iteration   1: 3.255 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.472 ms/op
                 createUser·p0.99:   7.867 ms/op
                 createUser·p0.999:  14.699 ms/op
                 createUser·p0.9999: 14.762 ms/op
                 createUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9820
  mean =      3.255 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1949 
    [ 2.500,  3.750) = 5756 
    [ 3.750,  5.000) = 1817 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.472 ms/op
     p(99.0000) =      7.867 ms/op
     p(99.9000) =     14.699 ms/op
     p(99.9900) =     14.762 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 3.325 ±(99.9%) 0.081 ms/op
Iteration   1: 1.797 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.680 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.176 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   4.023 ms/op
                 existUser·p0.999:  13.631 ms/op
                 existUser·p0.9999: 14.057 ms/op
                 existUser·p1.00:   14.631 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17786
  mean =      1.797 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 481 
    [ 1.250,  2.500) = 16553 
    [ 2.500,  3.750) = 547 
    [ 3.750,  5.000) = 127 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.176 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      4.023 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     14.057 ms/op
     p(99.9990) =     14.631 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 4.555 ±(99.9%) 0.103 ms/op
Iteration   1: 3.374 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   5.476 ms/op
                 getUser·p0.999:  9.102 ms/op
                 getUser·p0.9999: 9.667 ms/op
                 getUser·p1.00:   9.667 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9476
  mean =      3.374 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 192 
    [ 2.000,  3.000) = 2668 
    [ 3.000,  4.000) = 5233 
    [ 4.000,  5.000) = 1190 
    [ 5.000,  6.000) = 133 
    [ 6.000,  7.000) = 22 
    [ 7.000,  8.000) = 6 
    [ 8.000,  9.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.476 ms/op
     p(99.9000) =      9.102 ms/op
     p(99.9900) =      9.667 ms/op
     p(99.9990) =      9.667 ms/op
     p(99.9999) =      9.667 ms/op
    p(100.0000) =      9.667 ms/op


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
# Warmup Iteration   1: 12.989 ±(99.9%) 0.493 ms/op
Iteration   1: 9.225 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   3.789 ms/op
                 listUser·p0.50:   8.839 ms/op
                 listUser·p0.90:   12.322 ms/op
                 listUser·p0.95:   13.386 ms/op
                 listUser·p0.99:   15.090 ms/op
                 listUser·p0.999:  18.713 ms/op
                 listUser·p0.9999: 23.003 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3598
  mean =      9.225 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 23 
    [ 5.000,  7.500) = 779 
    [ 7.500, 10.000) = 1743 
    [10.000, 12.500) = 723 
    [12.500, 15.000) = 291 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.789 ms/op
     p(50.0000) =      8.839 ms/op
     p(90.0000) =     12.322 ms/op
     p(95.0000) =     13.386 ms/op
     p(99.0000) =     15.090 ms/op
     p(99.9000) =     18.713 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.963          ops/ms
Client.existUser                       thrpt         12.135          ops/ms
Client.getUser                         thrpt          7.903          ops/ms
Client.listUser                        thrpt          3.485          ops/ms
Client.createUser                       avgt          3.133           ms/op
Client.existUser                        avgt          1.899           ms/op
Client.getUser                          avgt          3.206           ms/op
Client.listUser                         avgt          9.971           ms/op
Client.createUser                     sample   9820   3.255 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          1.085           ms/op
Client.createUser:createUser·p0.50    sample          3.101           ms/op
Client.createUser:createUser·p0.90    sample          4.116           ms/op
Client.createUser:createUser·p0.95    sample          4.472           ms/op
Client.createUser:createUser·p0.99    sample          7.867           ms/op
Client.createUser:createUser·p0.999   sample         14.699           ms/op
Client.createUser:createUser·p0.9999  sample         14.762           ms/op
Client.createUser:createUser·p1.00    sample         14.762           ms/op
Client.existUser                      sample  17786   1.797 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.680           ms/op
Client.existUser:existUser·p0.50      sample          1.698           ms/op
Client.existUser:existUser·p0.90      sample          2.176           ms/op
Client.existUser:existUser·p0.95      sample          2.396           ms/op
Client.existUser:existUser·p0.99      sample          4.023           ms/op
Client.existUser:existUser·p0.999     sample         13.631           ms/op
Client.existUser:existUser·p0.9999    sample         14.057           ms/op
Client.existUser:existUser·p1.00      sample         14.631           ms/op
Client.getUser                        sample   9476   3.374 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.707           ms/op
Client.getUser:getUser·p0.50          sample          3.355           ms/op
Client.getUser:getUser·p0.90          sample          4.153           ms/op
Client.getUser:getUser·p0.95          sample          4.432           ms/op
Client.getUser:getUser·p0.99          sample          5.476           ms/op
Client.getUser:getUser·p0.999         sample          9.102           ms/op
Client.getUser:getUser·p0.9999        sample          9.667           ms/op
Client.getUser:getUser·p1.00          sample          9.667           ms/op
Client.listUser                       sample   3598   9.225 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample          3.789           ms/op
Client.listUser:listUser·p0.50        sample          8.839           ms/op
Client.listUser:listUser·p0.90        sample         12.322           ms/op
Client.listUser:listUser·p0.95        sample         13.386           ms/op
Client.listUser:listUser·p0.99        sample         15.090           ms/op
Client.listUser:listUser·p0.999       sample         18.713           ms/op
Client.listUser:listUser·p0.9999      sample         23.003           ms/op
Client.listUser:listUser·p1.00        sample         23.003           ms/op
