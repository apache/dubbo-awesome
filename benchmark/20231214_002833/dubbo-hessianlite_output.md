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
# Warmup Iteration   1: 2.060 ops/ms
Iteration   1: 5.460 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.460 ops/ms


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
# Warmup Iteration   1: 5.327 ops/ms
Iteration   1: 12.087 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.087 ops/ms


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
# Warmup Iteration   1: 4.426 ops/ms
Iteration   1: 8.734 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.734 ops/ms


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
# Warmup Iteration   1: 2.237 ops/ms
Iteration   1: 3.418 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.418 ops/ms


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
# Warmup Iteration   1: 5.368 ±(99.9%) 0.084 ms/op
Iteration   1: 3.095 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.095 ms/op


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
# Warmup Iteration   1: 3.175 ±(99.9%) 0.031 ms/op
Iteration   1: 1.800 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.800 ms/op


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
# Warmup Iteration   1: 4.481 ±(99.9%) 0.049 ms/op
Iteration   1: 3.460 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.460 ms/op


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
# Warmup Iteration   1: 11.882 ±(99.9%) 0.222 ms/op
Iteration   1: 8.007 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.007 ms/op


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
# Warmup Iteration   1: 4.917 ±(99.9%) 0.119 ms/op
Iteration   1: 3.168 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.894 ms/op
                 createUser·p0.999:  22.509 ms/op
                 createUser·p0.9999: 22.675 ms/op
                 createUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10079
  mean =      3.168 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1649 
    [ 2.500,  5.000) = 8148 
    [ 5.000,  7.500) = 216 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.894 ms/op
     p(99.9000) =     22.509 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 2.987 ±(99.9%) 0.060 ms/op
Iteration   1: 2.002 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   1.970 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.662 ms/op
                 existUser·p0.99:   2.996 ms/op
                 existUser·p0.999:  7.316 ms/op
                 existUser·p0.9999: 7.747 ms/op
                 existUser·p1.00:   7.889 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15961
  mean =      2.002 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 55 
    [1.000, 1.500) = 1673 
    [1.500, 2.000) = 6807 
    [2.000, 2.500) = 5799 
    [2.500, 3.000) = 1469 
    [3.000, 3.500) = 42 
    [3.500, 4.000) = 8 
    [4.000, 4.500) = 1 
    [4.500, 5.000) = 33 
    [5.000, 5.500) = 31 
    [5.500, 6.000) = 4 
    [6.000, 6.500) = 5 
    [6.500, 7.000) = 6 
    [7.000, 7.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.970 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.662 ms/op
     p(99.0000) =      2.996 ms/op
     p(99.9000) =      7.316 ms/op
     p(99.9900) =      7.747 ms/op
     p(99.9990) =      7.889 ms/op
     p(99.9999) =      7.889 ms/op
    p(100.0000) =      7.889 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.106 ms/op
Iteration   1: 2.894 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   2.658 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.184 ms/op
                 getUser·p0.999:  18.481 ms/op
                 getUser·p0.9999: 21.035 ms/op
                 getUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11056
  mean =      2.894 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3701 
    [ 2.500,  5.000) = 7230 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      2.658 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.184 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     21.035 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 11.894 ±(99.9%) 0.397 ms/op
Iteration   1: 8.513 ±(99.9%) 0.162 ms/op
                 listUser·p0.00:   3.224 ms/op
                 listUser·p0.50:   7.897 ms/op
                 listUser·p0.90:   11.207 ms/op
                 listUser·p0.95:   12.427 ms/op
                 listUser·p0.99:   19.992 ms/op
                 listUser·p0.999:  35.409 ms/op
                 listUser·p0.9999: 38.011 ms/op
                 listUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3869
  mean =      8.513 ±(99.9%) 0.162 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 82 
    [ 5.000,  7.500) = 1421 
    [ 7.500, 10.000) = 1584 
    [10.000, 12.500) = 599 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      3.224 ms/op
     p(50.0000) =      7.897 ms/op
     p(90.0000) =     11.207 ms/op
     p(95.0000) =     12.427 ms/op
     p(99.0000) =     19.992 ms/op
     p(99.9000) =     35.409 ms/op
     p(99.9900) =     38.011 ms/op
     p(99.9990) =     38.011 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.460          ops/ms
Client.existUser                       thrpt         12.087          ops/ms
Client.getUser                         thrpt          8.734          ops/ms
Client.listUser                        thrpt          3.418          ops/ms
Client.createUser                       avgt          3.095           ms/op
Client.existUser                        avgt          1.800           ms/op
Client.getUser                          avgt          3.460           ms/op
Client.listUser                         avgt          8.007           ms/op
Client.createUser                     sample  10079   3.168 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample          1.165           ms/op
Client.createUser:createUser·p0.50    sample          2.994           ms/op
Client.createUser:createUser·p0.90    sample          3.887           ms/op
Client.createUser:createUser·p0.95    sample          4.555           ms/op
Client.createUser:createUser·p0.99    sample          6.894           ms/op
Client.createUser:createUser·p0.999   sample         22.509           ms/op
Client.createUser:createUser·p0.9999  sample         22.675           ms/op
Client.createUser:createUser·p1.00    sample         22.675           ms/op
Client.existUser                      sample  15961   2.002 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.598           ms/op
Client.existUser:existUser·p0.50      sample          1.970           ms/op
Client.existUser:existUser·p0.90      sample          2.507           ms/op
Client.existUser:existUser·p0.95      sample          2.662           ms/op
Client.existUser:existUser·p0.99      sample          2.996           ms/op
Client.existUser:existUser·p0.999     sample          7.316           ms/op
Client.existUser:existUser·p0.9999    sample          7.747           ms/op
Client.existUser:existUser·p1.00      sample          7.889           ms/op
Client.getUser                        sample  11056   2.894 ± 0.037   ms/op
Client.getUser:getUser·p0.00          sample          1.023           ms/op
Client.getUser:getUser·p0.50          sample          2.658           ms/op
Client.getUser:getUser·p0.90          sample          3.600           ms/op
Client.getUser:getUser·p0.95          sample          3.936           ms/op
Client.getUser:getUser·p0.99          sample          5.184           ms/op
Client.getUser:getUser·p0.999         sample         18.481           ms/op
Client.getUser:getUser·p0.9999        sample         21.035           ms/op
Client.getUser:getUser·p1.00          sample         21.135           ms/op
Client.listUser                       sample   3869   8.513 ± 0.162   ms/op
Client.listUser:listUser·p0.00        sample          3.224           ms/op
Client.listUser:listUser·p0.50        sample          7.897           ms/op
Client.listUser:listUser·p0.90        sample         11.207           ms/op
Client.listUser:listUser·p0.95        sample         12.427           ms/op
Client.listUser:listUser·p0.99        sample         19.992           ms/op
Client.listUser:listUser·p0.999       sample         35.409           ms/op
Client.listUser:listUser·p0.9999      sample         38.011           ms/op
Client.listUser:listUser·p1.00        sample         38.011           ms/op
