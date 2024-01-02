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
# Warmup Iteration   1: 2.299 ops/ms
Iteration   1: 5.671 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.671 ops/ms


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
# Warmup Iteration   1: 5.824 ops/ms
Iteration   1: 10.958 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.958 ops/ms


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
# Warmup Iteration   1: 3.502 ops/ms
Iteration   1: 7.806 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.806 ops/ms


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
# Warmup Iteration   1: 1.987 ops/ms
Iteration   1: 4.124 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.124 ops/ms


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
# Warmup Iteration   1: 5.597 ±(99.9%) 0.057 ms/op
Iteration   1: 3.363 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.363 ms/op


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
# Warmup Iteration   1: 2.932 ±(99.9%) 0.029 ms/op
Iteration   1: 1.826 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.826 ms/op


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
# Warmup Iteration   1: 5.161 ±(99.9%) 0.064 ms/op
Iteration   1: 3.199 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.199 ms/op


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
# Warmup Iteration   1: 13.863 ±(99.9%) 0.322 ms/op
Iteration   1: 9.714 ±(99.9%) 0.125 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.714 ms/op


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
# Warmup Iteration   1: 5.182 ±(99.9%) 0.140 ms/op
Iteration   1: 3.047 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   2.847 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   7.783 ms/op
                 createUser·p0.999:  12.911 ms/op
                 createUser·p0.9999: 13.173 ms/op
                 createUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10496
  mean =      3.047 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1702 
    [ 2.500,  3.750) = 7881 
    [ 3.750,  5.000) = 590 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      7.783 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


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
# Warmup Iteration   1: 3.096 ±(99.9%) 0.078 ms/op
Iteration   1: 2.000 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.434 ms/op
                 existUser·p0.50:   1.950 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   3.024 ms/op
                 existUser·p0.999:  30.046 ms/op
                 existUser·p0.9999: 30.591 ms/op
                 existUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16076
  mean =      2.000 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14871 
    [ 2.500,  5.000) = 1140 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      1.950 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.024 ms/op
     p(99.9000) =     30.046 ms/op
     p(99.9900) =     30.591 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 4.535 ±(99.9%) 0.098 ms/op
Iteration   1: 3.100 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  16.293 ms/op
                 getUser·p0.9999: 17.690 ms/op
                 getUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10317
  mean =      3.100 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 2047 
    [ 2.500,  3.750) = 7013 
    [ 3.750,  5.000) = 1101 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     16.293 ms/op
     p(99.9900) =     17.690 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 12.616 ±(99.9%) 0.481 ms/op
Iteration   1: 8.707 ±(99.9%) 0.140 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   8.372 ms/op
                 listUser·p0.90:   11.646 ms/op
                 listUser·p0.95:   13.163 ms/op
                 listUser·p0.99:   18.068 ms/op
                 listUser·p0.999:  22.904 ms/op
                 listUser·p0.9999: 30.867 ms/op
                 listUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3671
  mean =      8.707 ±(99.9%) 0.140 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 113 
    [ 5.000,  7.500) = 1089 
    [ 7.500, 10.000) = 1598 
    [10.000, 12.500) = 613 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.354 ms/op
     p(50.0000) =      8.372 ms/op
     p(90.0000) =     11.646 ms/op
     p(95.0000) =     13.163 ms/op
     p(99.0000) =     18.068 ms/op
     p(99.9000) =     22.904 ms/op
     p(99.9900) =     30.867 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.671          ops/ms
Client.existUser                       thrpt         10.958          ops/ms
Client.getUser                         thrpt          7.806          ops/ms
Client.listUser                        thrpt          4.124          ops/ms
Client.createUser                       avgt          3.363           ms/op
Client.existUser                        avgt          1.826           ms/op
Client.getUser                          avgt          3.199           ms/op
Client.listUser                         avgt          9.714           ms/op
Client.createUser                     sample  10496   3.047 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.159           ms/op
Client.createUser:createUser·p0.50    sample          2.847           ms/op
Client.createUser:createUser·p0.90    sample          3.625           ms/op
Client.createUser:createUser·p0.95    sample          4.268           ms/op
Client.createUser:createUser·p0.99    sample          7.783           ms/op
Client.createUser:createUser·p0.999   sample         12.911           ms/op
Client.createUser:createUser·p0.9999  sample         13.173           ms/op
Client.createUser:createUser·p1.00    sample         13.173           ms/op
Client.existUser                      sample  16076   2.000 ± 0.034   ms/op
Client.existUser:existUser·p0.00      sample          0.434           ms/op
Client.existUser:existUser·p0.50      sample          1.950           ms/op
Client.existUser:existUser·p0.90      sample          2.433           ms/op
Client.existUser:existUser·p0.95      sample          2.597           ms/op
Client.existUser:existUser·p0.99      sample          3.024           ms/op
Client.existUser:existUser·p0.999     sample         30.046           ms/op
Client.existUser:existUser·p0.9999    sample         30.591           ms/op
Client.existUser:existUser·p1.00      sample         30.671           ms/op
Client.getUser                        sample  10317   3.100 ± 0.035   ms/op
Client.getUser:getUser·p0.00          sample          0.871           ms/op
Client.getUser:getUser·p0.50          sample          2.994           ms/op
Client.getUser:getUser·p0.90          sample          3.826           ms/op
Client.getUser:getUser·p0.95          sample          4.211           ms/op
Client.getUser:getUser·p0.99          sample          5.652           ms/op
Client.getUser:getUser·p0.999         sample         16.293           ms/op
Client.getUser:getUser·p0.9999        sample         17.690           ms/op
Client.getUser:getUser·p1.00          sample         17.695           ms/op
Client.listUser                       sample   3671   8.707 ± 0.140   ms/op
Client.listUser:listUser·p0.00        sample          1.354           ms/op
Client.listUser:listUser·p0.50        sample          8.372           ms/op
Client.listUser:listUser·p0.90        sample         11.646           ms/op
Client.listUser:listUser·p0.95        sample         13.163           ms/op
Client.listUser:listUser·p0.99        sample         18.068           ms/op
Client.listUser:listUser·p0.999       sample         22.904           ms/op
Client.listUser:listUser·p0.9999      sample         30.867           ms/op
Client.listUser:listUser·p1.00        sample         30.867           ms/op
