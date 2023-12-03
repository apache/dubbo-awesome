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
# Warmup Iteration   1: 2.268 ops/ms
Iteration   1: 6.443 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.443 ops/ms


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
# Warmup Iteration   1: 6.783 ops/ms
Iteration   1: 13.071 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.071 ops/ms


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
# Warmup Iteration   1: 4.508 ops/ms
Iteration   1: 7.393 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.393 ops/ms


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
# Warmup Iteration   1: 2.315 ops/ms
Iteration   1: 3.523 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.523 ops/ms


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
# Warmup Iteration   1: 5.183 ±(99.9%) 0.054 ms/op
Iteration   1: 3.012 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.012 ms/op


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
# Warmup Iteration   1: 3.045 ±(99.9%) 0.032 ms/op
Iteration   1: 2.183 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.183 ms/op


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
# Warmup Iteration   1: 4.480 ±(99.9%) 0.058 ms/op
Iteration   1: 2.759 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.759 ms/op


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
# Warmup Iteration   1: 11.873 ±(99.9%) 0.191 ms/op
Iteration   1: 8.797 ±(99.9%) 0.134 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.797 ms/op


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
# Warmup Iteration   1: 5.217 ±(99.9%) 0.114 ms/op
Iteration   1: 3.026 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   1.163 ms/op
                 createUser·p0.50:   2.748 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   11.013 ms/op
                 createUser·p0.999:  20.232 ms/op
                 createUser·p0.9999: 20.958 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10578
  mean =      3.026 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1960 
    [ 2.500,  5.000) = 8324 
    [ 5.000,  7.500) = 133 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      2.748 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =     11.013 ms/op
     p(99.9000) =     20.232 ms/op
     p(99.9900) =     20.958 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 2.964 ±(99.9%) 0.062 ms/op
Iteration   1: 1.701 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   1.616 ms/op
                 existUser·p0.90:   2.167 ms/op
                 existUser·p0.95:   2.400 ms/op
                 existUser·p0.99:   2.949 ms/op
                 existUser·p0.999:  3.798 ms/op
                 existUser·p0.9999: 5.665 ms/op
                 existUser·p1.00:   6.914 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18813
  mean =      1.701 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 44 
    [1.000, 1.500) = 4608 
    [1.500, 2.000) = 11337 
    [2.000, 2.500) = 2129 
    [2.500, 3.000) = 529 
    [3.000, 3.500) = 121 
    [3.500, 4.000) = 32 
    [4.000, 4.500) = 4 
    [4.500, 5.000) = 7 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      1.616 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.400 ms/op
     p(99.0000) =      2.949 ms/op
     p(99.9000) =      3.798 ms/op
     p(99.9900) =      5.665 ms/op
     p(99.9990) =      6.914 ms/op
     p(99.9999) =      6.914 ms/op
    p(100.0000) =      6.914 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.099 ms/op
Iteration   1: 2.760 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  22.098 ms/op
                 getUser·p0.9999: 22.206 ms/op
                 getUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11614
  mean =      2.760 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5390 
    [ 2.500,  5.000) = 6137 
    [ 5.000,  7.500) = 22 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     22.098 ms/op
     p(99.9900) =     22.206 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 11.043 ±(99.9%) 0.382 ms/op
Iteration   1: 8.004 ±(99.9%) 0.122 ms/op
                 listUser·p0.00:   2.998 ms/op
                 listUser·p0.50:   7.479 ms/op
                 listUser·p0.90:   10.764 ms/op
                 listUser·p0.95:   12.193 ms/op
                 listUser·p0.99:   17.334 ms/op
                 listUser·p0.999:  19.432 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3995
  mean =      8.004 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 166 
    [ 5.000,  7.500) = 1843 
    [ 7.500, 10.000) = 1338 
    [10.000, 12.500) = 486 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.998 ms/op
     p(50.0000) =      7.479 ms/op
     p(90.0000) =     10.764 ms/op
     p(95.0000) =     12.193 ms/op
     p(99.0000) =     17.334 ms/op
     p(99.9000) =     19.432 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.443          ops/ms
Client.existUser                       thrpt         13.071          ops/ms
Client.getUser                         thrpt          7.393          ops/ms
Client.listUser                        thrpt          3.523          ops/ms
Client.createUser                       avgt          3.012           ms/op
Client.existUser                        avgt          2.183           ms/op
Client.getUser                          avgt          2.759           ms/op
Client.listUser                         avgt          8.797           ms/op
Client.createUser                     sample  10578   3.026 ± 0.049   ms/op
Client.createUser:createUser·p0.00    sample          1.163           ms/op
Client.createUser:createUser·p0.50    sample          2.748           ms/op
Client.createUser:createUser·p0.90    sample          3.506           ms/op
Client.createUser:createUser·p0.95    sample          4.440           ms/op
Client.createUser:createUser·p0.99    sample         11.013           ms/op
Client.createUser:createUser·p0.999   sample         20.232           ms/op
Client.createUser:createUser·p0.9999  sample         20.958           ms/op
Client.createUser:createUser·p1.00    sample         20.972           ms/op
Client.existUser                      sample  18813   1.701 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.535           ms/op
Client.existUser:existUser·p0.50      sample          1.616           ms/op
Client.existUser:existUser·p0.90      sample          2.167           ms/op
Client.existUser:existUser·p0.95      sample          2.400           ms/op
Client.existUser:existUser·p0.99      sample          2.949           ms/op
Client.existUser:existUser·p0.999     sample          3.798           ms/op
Client.existUser:existUser·p0.9999    sample          5.665           ms/op
Client.existUser:existUser·p1.00      sample          6.914           ms/op
Client.getUser                        sample  11614   2.760 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          0.975           ms/op
Client.getUser:getUser·p0.50          sample          2.544           ms/op
Client.getUser:getUser·p0.90          sample          3.457           ms/op
Client.getUser:getUser·p0.95          sample          3.674           ms/op
Client.getUser:getUser·p0.99          sample          4.604           ms/op
Client.getUser:getUser·p0.999         sample         22.098           ms/op
Client.getUser:getUser·p0.9999        sample         22.206           ms/op
Client.getUser:getUser·p1.00          sample         22.217           ms/op
Client.listUser                       sample   3995   8.004 ± 0.122   ms/op
Client.listUser:listUser·p0.00        sample          2.998           ms/op
Client.listUser:listUser·p0.50        sample          7.479           ms/op
Client.listUser:listUser·p0.90        sample         10.764           ms/op
Client.listUser:listUser·p0.95        sample         12.193           ms/op
Client.listUser:listUser·p0.99        sample         17.334           ms/op
Client.listUser:listUser·p0.999       sample         19.432           ms/op
Client.listUser:listUser·p0.9999      sample         21.463           ms/op
Client.listUser:listUser·p1.00        sample         21.463           ms/op
