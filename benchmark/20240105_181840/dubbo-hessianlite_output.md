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
# Warmup Iteration   1: 2.029 ops/ms
Iteration   1: 5.044 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.044 ops/ms


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
# Warmup Iteration   1: 5.522 ops/ms
Iteration   1: 12.035 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.035 ops/ms


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
# Warmup Iteration   1: 3.649 ops/ms
Iteration   1: 8.039 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.039 ops/ms


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
# Warmup Iteration   1: 2.037 ops/ms
Iteration   1: 3.336 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.336 ops/ms


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
# Warmup Iteration   1: 5.666 ±(99.9%) 0.089 ms/op
Iteration   1: 3.657 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.657 ms/op


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
# Warmup Iteration   1: 3.745 ±(99.9%) 0.038 ms/op
Iteration   1: 2.083 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.083 ms/op


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
# Warmup Iteration   1: 5.175 ±(99.9%) 0.059 ms/op
Iteration   1: 3.101 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.101 ms/op


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
# Warmup Iteration   1: 13.308 ±(99.9%) 0.223 ms/op
Iteration   1: 8.246 ±(99.9%) 0.075 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.246 ms/op


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
# Warmup Iteration   1: 5.331 ±(99.9%) 0.133 ms/op
Iteration   1: 3.343 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   1.774 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   10.411 ms/op
                 createUser·p0.999:  21.856 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9557
  mean =      3.343 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 519 
    [ 2.500,  5.000) = 8762 
    [ 5.000,  7.500) = 138 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.774 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =     10.411 ms/op
     p(99.9000) =     21.856 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.081 ms/op
Iteration   1: 1.870 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.574 ms/op
                 existUser·p0.50:   1.774 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.421 ms/op
                 existUser·p0.99:   3.199 ms/op
                 existUser·p0.999:  16.122 ms/op
                 existUser·p0.9999: 16.782 ms/op
                 existUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17107
  mean =      1.870 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 358 
    [ 1.250,  2.500) = 16100 
    [ 2.500,  3.750) = 530 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      1.774 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.421 ms/op
     p(99.0000) =      3.199 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     16.782 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 4.458 ±(99.9%) 0.112 ms/op
Iteration   1: 3.428 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   1.483 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.245 ms/op
                 getUser·p0.999:  15.892 ms/op
                 getUser·p0.9999: 17.039 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9371
  mean =      3.428 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1210 
    [ 2.500,  3.750) = 5558 
    [ 3.750,  5.000) = 2364 
    [ 5.000,  6.250) = 146 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.245 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 12.652 ±(99.9%) 0.439 ms/op
Iteration   1: 8.492 ±(99.9%) 0.134 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   8.077 ms/op
                 listUser·p0.90:   11.108 ms/op
                 listUser·p0.95:   12.141 ms/op
                 listUser·p0.99:   19.939 ms/op
                 listUser·p0.999:  25.049 ms/op
                 listUser·p0.9999: 25.330 ms/op
                 listUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3850
  mean =      8.492 ±(99.9%) 0.134 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 68 
    [ 5.000,  7.500) = 1303 
    [ 7.500, 10.000) = 1791 
    [10.000, 12.500) = 522 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.281 ms/op
     p(50.0000) =      8.077 ms/op
     p(90.0000) =     11.108 ms/op
     p(95.0000) =     12.141 ms/op
     p(99.0000) =     19.939 ms/op
     p(99.9000) =     25.049 ms/op
     p(99.9900) =     25.330 ms/op
     p(99.9990) =     25.330 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.044          ops/ms
Client.existUser                       thrpt         12.035          ops/ms
Client.getUser                         thrpt          8.039          ops/ms
Client.listUser                        thrpt          3.336          ops/ms
Client.createUser                       avgt          3.657           ms/op
Client.existUser                        avgt          2.083           ms/op
Client.getUser                          avgt          3.101           ms/op
Client.listUser                         avgt          8.246           ms/op
Client.createUser                     sample   9557   3.343 ± 0.048   ms/op
Client.createUser:createUser·p0.00    sample          1.774           ms/op
Client.createUser:createUser·p0.50    sample          3.084           ms/op
Client.createUser:createUser·p0.90    sample          3.994           ms/op
Client.createUser:createUser·p0.95    sample          4.415           ms/op
Client.createUser:createUser·p0.99    sample         10.411           ms/op
Client.createUser:createUser·p0.999   sample         21.856           ms/op
Client.createUser:createUser·p0.9999  sample         22.774           ms/op
Client.createUser:createUser·p1.00    sample         22.774           ms/op
Client.existUser                      sample  17107   1.870 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.574           ms/op
Client.existUser:existUser·p0.50      sample          1.774           ms/op
Client.existUser:existUser·p0.90      sample          2.281           ms/op
Client.existUser:existUser·p0.95      sample          2.421           ms/op
Client.existUser:existUser·p0.99      sample          3.199           ms/op
Client.existUser:existUser·p0.999     sample         16.122           ms/op
Client.existUser:existUser·p0.9999    sample         16.782           ms/op
Client.existUser:existUser·p1.00      sample         16.876           ms/op
Client.getUser                        sample   9371   3.428 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          1.483           ms/op
Client.getUser:getUser·p0.50          sample          3.424           ms/op
Client.getUser:getUser·p0.90          sample          4.182           ms/op
Client.getUser:getUser·p0.95          sample          4.514           ms/op
Client.getUser:getUser·p0.99          sample          6.245           ms/op
Client.getUser:getUser·p0.999         sample         15.892           ms/op
Client.getUser:getUser·p0.9999        sample         17.039           ms/op
Client.getUser:getUser·p1.00          sample         17.039           ms/op
Client.listUser                       sample   3850   8.492 ± 0.134   ms/op
Client.listUser:listUser·p0.00        sample          2.281           ms/op
Client.listUser:listUser·p0.50        sample          8.077           ms/op
Client.listUser:listUser·p0.90        sample         11.108           ms/op
Client.listUser:listUser·p0.95        sample         12.141           ms/op
Client.listUser:listUser·p0.99        sample         19.939           ms/op
Client.listUser:listUser·p0.999       sample         25.049           ms/op
Client.listUser:listUser·p0.9999      sample         25.330           ms/op
Client.listUser:listUser·p1.00        sample         25.330           ms/op
