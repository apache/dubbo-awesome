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
# Warmup Iteration   1: 2.494 ops/ms
Iteration   1: 6.073 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.073 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.752 ops/ms
Iteration   1: 13.381 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.381 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.293 ops/ms
Iteration   1: 9.324 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.324 ops/ms


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
# Warmup Iteration   1: 1.850 ops/ms
Iteration   1: 3.174 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.174 ops/ms


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
# Warmup Iteration   1: 5.272 ±(99.9%) 0.060 ms/op
Iteration   1: 3.242 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.242 ms/op


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
# Warmup Iteration   1: 3.162 ±(99.9%) 0.027 ms/op
Iteration   1: 1.714 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.714 ms/op


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
# Warmup Iteration   1: 4.690 ±(99.9%) 0.062 ms/op
Iteration   1: 3.264 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.264 ms/op


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
# Warmup Iteration   1: 13.194 ±(99.9%) 0.195 ms/op
Iteration   1: 8.252 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.252 ms/op


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
# Warmup Iteration   1: 4.880 ±(99.9%) 0.102 ms/op
Iteration   1: 2.862 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.703 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.631 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 8.825 ms/op
                 createUser·p1.00:   8.831 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11168
  mean =      2.862 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 24 
    [1.500, 2.000) = 392 
    [2.000, 2.500) = 3373 
    [2.500, 3.000) = 3051 
    [3.000, 3.500) = 2505 
    [3.500, 4.000) = 1616 
    [4.000, 4.500) = 86 
    [4.500, 5.000) = 52 
    [5.000, 5.500) = 22 
    [5.500, 6.000) = 6 
    [6.000, 6.500) = 1 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      2.703 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.631 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =      8.825 ms/op
     p(99.9990) =      8.831 ms/op
     p(99.9999) =      8.831 ms/op
    p(100.0000) =      8.831 ms/op


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
# Warmup Iteration   1: 3.219 ±(99.9%) 0.131 ms/op
Iteration   1: 1.860 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   1.835 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   3.249 ms/op
                 existUser·p0.999:  5.921 ms/op
                 existUser·p0.9999: 6.519 ms/op
                 existUser·p1.00:   6.889 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17184
  mean =      1.860 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 69 
    [1.000, 1.500) = 3151 
    [1.500, 2.000) = 8334 
    [2.000, 2.500) = 4854 
    [2.500, 3.000) = 545 
    [3.000, 3.500) = 85 
    [3.500, 4.000) = 61 
    [4.000, 4.500) = 12 
    [4.500, 5.000) = 28 
    [5.000, 5.500) = 21 
    [5.500, 6.000) = 14 
    [6.000, 6.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.249 ms/op
     p(99.9000) =      5.921 ms/op
     p(99.9900) =      6.519 ms/op
     p(99.9990) =      6.889 ms/op
     p(99.9999) =      6.889 ms/op
    p(100.0000) =      6.889 ms/op


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.109 ms/op
Iteration   1: 3.003 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   2.904 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  7.422 ms/op
                 getUser·p0.9999: 9.576 ms/op
                 getUser·p1.00:   9.585 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10712
  mean =      3.003 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 8 
    [ 1.000,  2.000) = 431 
    [ 2.000,  3.000) = 5331 
    [ 3.000,  4.000) = 4221 
    [ 4.000,  5.000) = 530 
    [ 5.000,  6.000) = 107 
    [ 6.000,  7.000) = 36 
    [ 7.000,  8.000) = 41 
    [ 8.000,  9.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      7.422 ms/op
     p(99.9900) =      9.576 ms/op
     p(99.9990) =      9.585 ms/op
     p(99.9999) =      9.585 ms/op
    p(100.0000) =      9.585 ms/op


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
# Warmup Iteration   1: 13.626 ±(99.9%) 0.558 ms/op
Iteration   1: 7.867 ±(99.9%) 0.103 ms/op
                 listUser·p0.00:   3.006 ms/op
                 listUser·p0.50:   7.700 ms/op
                 listUser·p0.90:   10.076 ms/op
                 listUser·p0.95:   10.985 ms/op
                 listUser·p0.99:   15.606 ms/op
                 listUser·p0.999:  21.201 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4074
  mean =      7.867 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 114 
    [ 5.000,  7.500) = 1730 
    [ 7.500, 10.000) = 1807 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.006 ms/op
     p(50.0000) =      7.700 ms/op
     p(90.0000) =     10.076 ms/op
     p(95.0000) =     10.985 ms/op
     p(99.0000) =     15.606 ms/op
     p(99.9000) =     21.201 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     24.019 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.073          ops/ms
Client.existUser                       thrpt         13.381          ops/ms
Client.getUser                         thrpt          9.324          ops/ms
Client.listUser                        thrpt          3.174          ops/ms
Client.createUser                       avgt          3.242           ms/op
Client.existUser                        avgt          1.714           ms/op
Client.getUser                          avgt          3.264           ms/op
Client.listUser                         avgt          8.252           ms/op
Client.createUser                     sample  11168   2.862 ± 0.021   ms/op
Client.createUser:createUser·p0.00    sample          1.057           ms/op
Client.createUser:createUser·p0.50    sample          2.703           ms/op
Client.createUser:createUser·p0.90    sample          3.727           ms/op
Client.createUser:createUser·p0.95    sample          3.826           ms/op
Client.createUser:createUser·p0.99    sample          4.631           ms/op
Client.createUser:createUser·p0.999   sample          8.634           ms/op
Client.createUser:createUser·p0.9999  sample          8.825           ms/op
Client.createUser:createUser·p1.00    sample          8.831           ms/op
Client.existUser                      sample  17184   1.860 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.631           ms/op
Client.existUser:existUser·p0.50      sample          1.835           ms/op
Client.existUser:existUser·p0.90      sample          2.310           ms/op
Client.existUser:existUser·p0.95      sample          2.478           ms/op
Client.existUser:existUser·p0.99      sample          3.249           ms/op
Client.existUser:existUser·p0.999     sample          5.921           ms/op
Client.existUser:existUser·p0.9999    sample          6.519           ms/op
Client.existUser:existUser·p1.00      sample          6.889           ms/op
Client.getUser                        sample  10712   3.003 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          0.723           ms/op
Client.getUser:getUser·p0.50          sample          2.904           ms/op
Client.getUser:getUser·p0.90          sample          3.838           ms/op
Client.getUser:getUser·p0.95          sample          4.116           ms/op
Client.getUser:getUser·p0.99          sample          5.661           ms/op
Client.getUser:getUser·p0.999         sample          7.422           ms/op
Client.getUser:getUser·p0.9999        sample          9.576           ms/op
Client.getUser:getUser·p1.00          sample          9.585           ms/op
Client.listUser                       sample   4074   7.867 ± 0.103   ms/op
Client.listUser:listUser·p0.00        sample          3.006           ms/op
Client.listUser:listUser·p0.50        sample          7.700           ms/op
Client.listUser:listUser·p0.90        sample         10.076           ms/op
Client.listUser:listUser·p0.95        sample         10.985           ms/op
Client.listUser:listUser·p0.99        sample         15.606           ms/op
Client.listUser:listUser·p0.999       sample         21.201           ms/op
Client.listUser:listUser·p0.9999      sample         24.019           ms/op
Client.listUser:listUser·p1.00        sample         24.019           ms/op
