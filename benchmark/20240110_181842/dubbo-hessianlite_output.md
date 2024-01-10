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
# Warmup Iteration   1: 2.207 ops/ms
Iteration   1: 6.602 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.602 ops/ms


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
# Warmup Iteration   1: 5.330 ops/ms
Iteration   1: 12.732 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.732 ops/ms


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
# Warmup Iteration   1: 3.519 ops/ms
Iteration   1: 8.335 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.335 ops/ms


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
# Warmup Iteration   1: 2.047 ops/ms
Iteration   1: 3.686 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.686 ops/ms


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
# Warmup Iteration   1: 5.242 ±(99.9%) 0.076 ms/op
Iteration   1: 3.126 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.126 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.041 ms/op
Iteration   1: 1.933 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.933 ms/op


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
# Warmup Iteration   1: 4.892 ±(99.9%) 0.057 ms/op
Iteration   1: 2.930 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.930 ms/op


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
# Warmup Iteration   1: 12.079 ±(99.9%) 0.158 ms/op
Iteration   1: 8.508 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.508 ms/op


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
# Warmup Iteration   1: 4.844 ±(99.9%) 0.093 ms/op
Iteration   1: 3.029 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   2.863 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   11.540 ms/op
                 createUser·p0.999:  12.965 ms/op
                 createUser·p0.9999: 13.295 ms/op
                 createUser·p1.00:   13.304 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10663
  mean =      3.029 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2521 
    [ 2.500,  3.750) = 7365 
    [ 3.750,  5.000) = 453 
    [ 5.000,  6.250) = 135 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      4.116 ms/op
     p(99.0000) =     11.540 ms/op
     p(99.9000) =     12.965 ms/op
     p(99.9900) =     13.295 ms/op
     p(99.9990) =     13.304 ms/op
     p(99.9999) =     13.304 ms/op
    p(100.0000) =     13.304 ms/op


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
# Warmup Iteration   1: 3.316 ±(99.9%) 0.086 ms/op
Iteration   1: 1.869 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.720 ms/op
                 existUser·p0.99:   3.178 ms/op
                 existUser·p0.999:  4.832 ms/op
                 existUser·p0.9999: 7.036 ms/op
                 existUser·p1.00:   7.397 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17110
  mean =      1.869 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 183 
    [1.000, 1.500) = 3043 
    [1.500, 2.000) = 8510 
    [2.000, 2.500) = 3951 
    [2.500, 3.000) = 1045 
    [3.000, 3.500) = 283 
    [3.500, 4.000) = 30 
    [4.000, 4.500) = 12 
    [4.500, 5.000) = 44 
    [5.000, 5.500) = 4 
    [5.500, 6.000) = 2 
    [6.000, 6.500) = 1 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.178 ms/op
     p(99.9000) =      4.832 ms/op
     p(99.9900) =      7.036 ms/op
     p(99.9990) =      7.397 ms/op
     p(99.9999) =      7.397 ms/op
    p(100.0000) =      7.397 ms/op


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
# Warmup Iteration   1: 4.749 ±(99.9%) 0.126 ms/op
Iteration   1: 3.142 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  6.846 ms/op
                 getUser·p0.9999: 11.444 ms/op
                 getUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10182
  mean =      3.142 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 2007 
    [ 2.500,  3.750) = 5759 
    [ 3.750,  5.000) = 2271 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      6.846 ms/op
     p(99.9900) =     11.444 ms/op
     p(99.9990) =     11.485 ms/op
     p(99.9999) =     11.485 ms/op
    p(100.0000) =     11.485 ms/op


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
# Warmup Iteration   1: 12.018 ±(99.9%) 0.402 ms/op
Iteration   1: 7.736 ±(99.9%) 0.147 ms/op
                 listUser·p0.00:   3.285 ms/op
                 listUser·p0.50:   7.234 ms/op
                 listUser·p0.90:   9.781 ms/op
                 listUser·p0.95:   11.174 ms/op
                 listUser·p0.99:   18.824 ms/op
                 listUser·p0.999:  32.904 ms/op
                 listUser·p0.9999: 37.487 ms/op
                 listUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4152
  mean =      7.736 ±(99.9%) 0.147 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 154 
    [ 5.000,  7.500) = 2215 
    [ 7.500, 10.000) = 1417 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.285 ms/op
     p(50.0000) =      7.234 ms/op
     p(90.0000) =      9.781 ms/op
     p(95.0000) =     11.174 ms/op
     p(99.0000) =     18.824 ms/op
     p(99.9000) =     32.904 ms/op
     p(99.9900) =     37.487 ms/op
     p(99.9990) =     37.487 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.602          ops/ms
Client.existUser                       thrpt         12.732          ops/ms
Client.getUser                         thrpt          8.335          ops/ms
Client.listUser                        thrpt          3.686          ops/ms
Client.createUser                       avgt          3.126           ms/op
Client.existUser                        avgt          1.933           ms/op
Client.getUser                          avgt          2.930           ms/op
Client.listUser                         avgt          8.508           ms/op
Client.createUser                     sample  10663   3.029 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.397           ms/op
Client.createUser:createUser·p0.50    sample          2.863           ms/op
Client.createUser:createUser·p0.90    sample          3.576           ms/op
Client.createUser:createUser·p0.95    sample          4.116           ms/op
Client.createUser:createUser·p0.99    sample         11.540           ms/op
Client.createUser:createUser·p0.999   sample         12.965           ms/op
Client.createUser:createUser·p0.9999  sample         13.295           ms/op
Client.createUser:createUser·p1.00    sample         13.304           ms/op
Client.existUser                      sample  17110   1.869 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.791           ms/op
Client.existUser:existUser·p0.50      sample          1.796           ms/op
Client.existUser:existUser·p0.90      sample          2.429           ms/op
Client.existUser:existUser·p0.95      sample          2.720           ms/op
Client.existUser:existUser·p0.99      sample          3.178           ms/op
Client.existUser:existUser·p0.999     sample          4.832           ms/op
Client.existUser:existUser·p0.9999    sample          7.036           ms/op
Client.existUser:existUser·p1.00      sample          7.397           ms/op
Client.getUser                        sample  10182   3.142 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.568           ms/op
Client.getUser:getUser·p0.50          sample          3.101           ms/op
Client.getUser:getUser·p0.90          sample          4.137           ms/op
Client.getUser:getUser·p0.95          sample          4.342           ms/op
Client.getUser:getUser·p0.99          sample          4.858           ms/op
Client.getUser:getUser·p0.999         sample          6.846           ms/op
Client.getUser:getUser·p0.9999        sample         11.444           ms/op
Client.getUser:getUser·p1.00          sample         11.485           ms/op
Client.listUser                       sample   4152   7.736 ± 0.147   ms/op
Client.listUser:listUser·p0.00        sample          3.285           ms/op
Client.listUser:listUser·p0.50        sample          7.234           ms/op
Client.listUser:listUser·p0.90        sample          9.781           ms/op
Client.listUser:listUser·p0.95        sample         11.174           ms/op
Client.listUser:listUser·p0.99        sample         18.824           ms/op
Client.listUser:listUser·p0.999       sample         32.904           ms/op
Client.listUser:listUser·p0.9999      sample         37.487           ms/op
Client.listUser:listUser·p1.00        sample         37.487           ms/op
