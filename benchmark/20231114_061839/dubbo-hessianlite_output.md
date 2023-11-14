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
# Warmup Iteration   1: 2.278 ops/ms
Iteration   1: 6.112 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.112 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.449 ops/ms
Iteration   1: 14.412 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.412 ops/ms


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
# Warmup Iteration   1: 4.953 ops/ms
Iteration   1: 8.571 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.571 ops/ms


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
# Warmup Iteration   1: 2.197 ops/ms
Iteration   1: 4.110 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.110 ops/ms


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
# Warmup Iteration   1: 4.847 ±(99.9%) 0.064 ms/op
Iteration   1: 3.032 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.032 ms/op


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
# Warmup Iteration   1: 2.894 ±(99.9%) 0.032 ms/op
Iteration   1: 1.893 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.893 ms/op


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
# Warmup Iteration   1: 4.964 ±(99.9%) 0.106 ms/op
Iteration   1: 3.153 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.153 ms/op


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
# Warmup Iteration   1: 12.144 ±(99.9%) 0.195 ms/op
Iteration   1: 7.703 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.703 ms/op


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
# Warmup Iteration   1: 4.777 ±(99.9%) 0.089 ms/op
Iteration   1: 3.395 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.595 ms/op
                 createUser·p0.99:   6.805 ms/op
                 createUser·p0.999:  7.906 ms/op
                 createUser·p0.9999: 12.124 ms/op
                 createUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9632
  mean =      3.395 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1705 
    [ 2.500,  3.750) = 5286 
    [ 3.750,  5.000) = 1790 
    [ 5.000,  6.250) = 732 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.805 ms/op
     p(99.9000) =      7.906 ms/op
     p(99.9900) =     12.124 ms/op
     p(99.9990) =     12.124 ms/op
     p(99.9999) =     12.124 ms/op
    p(100.0000) =     12.124 ms/op


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
# Warmup Iteration   1: 2.845 ±(99.9%) 0.056 ms/op
Iteration   1: 1.974 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   1.905 ms/op
                 existUser·p0.90:   2.472 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  19.477 ms/op
                 existUser·p0.9999: 20.444 ms/op
                 existUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16204
  mean =      1.974 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14717 
    [ 2.500,  5.000) = 1408 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.472 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =     19.477 ms/op
     p(99.9900) =     20.444 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.102 ms/op
Iteration   1: 3.011 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   2.908 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.775 ms/op
                 getUser·p0.999:  13.952 ms/op
                 getUser·p0.9999: 16.917 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10807
  mean =      3.011 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 2660 
    [ 2.500,  3.750) = 6975 
    [ 3.750,  5.000) = 981 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     13.952 ms/op
     p(99.9900) =     16.917 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 11.678 ±(99.9%) 0.457 ms/op
Iteration   1: 8.310 ±(99.9%) 0.114 ms/op
                 listUser·p0.00:   3.596 ms/op
                 listUser·p0.50:   7.930 ms/op
                 listUser·p0.90:   11.174 ms/op
                 listUser·p0.95:   12.265 ms/op
                 listUser·p0.99:   14.909 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3847
  mean =      8.310 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 2 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 493 
    [ 6.250,  7.500) = 919 
    [ 7.500,  8.750) = 1092 
    [ 8.750, 10.000) = 424 
    [10.000, 11.250) = 464 
    [11.250, 12.500) = 191 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      3.596 ms/op
     p(50.0000) =      7.930 ms/op
     p(90.0000) =     11.174 ms/op
     p(95.0000) =     12.265 ms/op
     p(99.0000) =     14.909 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.112          ops/ms
Client.existUser                       thrpt         14.412          ops/ms
Client.getUser                         thrpt          8.571          ops/ms
Client.listUser                        thrpt          4.110          ops/ms
Client.createUser                       avgt          3.032           ms/op
Client.existUser                        avgt          1.893           ms/op
Client.getUser                          avgt          3.153           ms/op
Client.listUser                         avgt          7.703           ms/op
Client.createUser                     sample   9632   3.395 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.397           ms/op
Client.createUser:createUser·p0.50    sample          3.195           ms/op
Client.createUser:createUser·p0.90    sample          4.792           ms/op
Client.createUser:createUser·p0.95    sample          5.595           ms/op
Client.createUser:createUser·p0.99    sample          6.805           ms/op
Client.createUser:createUser·p0.999   sample          7.906           ms/op
Client.createUser:createUser·p0.9999  sample         12.124           ms/op
Client.createUser:createUser·p1.00    sample         12.124           ms/op
Client.existUser                      sample  16204   1.974 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.588           ms/op
Client.existUser:existUser·p0.50      sample          1.905           ms/op
Client.existUser:existUser·p0.90      sample          2.472           ms/op
Client.existUser:existUser·p0.95      sample          2.642           ms/op
Client.existUser:existUser·p0.99      sample          3.572           ms/op
Client.existUser:existUser·p0.999     sample         19.477           ms/op
Client.existUser:existUser·p0.9999    sample         20.444           ms/op
Client.existUser:existUser·p1.00      sample         20.546           ms/op
Client.getUser                        sample  10807   3.011 ± 0.030   ms/op
Client.getUser:getUser·p0.00          sample          1.108           ms/op
Client.getUser:getUser·p0.50          sample          2.908           ms/op
Client.getUser:getUser·p0.90          sample          3.797           ms/op
Client.getUser:getUser·p0.95          sample          4.194           ms/op
Client.getUser:getUser·p0.99          sample          6.775           ms/op
Client.getUser:getUser·p0.999         sample         13.952           ms/op
Client.getUser:getUser·p0.9999        sample         16.917           ms/op
Client.getUser:getUser·p1.00          sample         17.007           ms/op
Client.listUser                       sample   3847   8.310 ± 0.114   ms/op
Client.listUser:listUser·p0.00        sample          3.596           ms/op
Client.listUser:listUser·p0.50        sample          7.930           ms/op
Client.listUser:listUser·p0.90        sample         11.174           ms/op
Client.listUser:listUser·p0.95        sample         12.265           ms/op
Client.listUser:listUser·p0.99        sample         14.909           ms/op
Client.listUser:listUser·p0.999       sample         18.088           ms/op
Client.listUser:listUser·p0.9999      sample         19.366           ms/op
Client.listUser:listUser·p1.00        sample         19.366           ms/op
