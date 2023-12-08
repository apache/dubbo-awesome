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
# Warmup Iteration   1: 2.513 ops/ms
Iteration   1: 6.120 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.120 ops/ms


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
# Warmup Iteration   1: 5.548 ops/ms
Iteration   1: 12.483 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.483 ops/ms


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
# Warmup Iteration   1: 4.315 ops/ms
Iteration   1: 8.471 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.471 ops/ms


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
# Warmup Iteration   1: 2.269 ops/ms
Iteration   1: 3.248 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.248 ops/ms


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
# Warmup Iteration   1: 5.076 ±(99.9%) 0.055 ms/op
Iteration   1: 3.030 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.030 ms/op


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
# Warmup Iteration   1: 3.333 ±(99.9%) 0.038 ms/op
Iteration   1: 1.810 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.810 ms/op


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
# Warmup Iteration   1: 4.814 ±(99.9%) 0.046 ms/op
Iteration   1: 2.703 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.703 ms/op


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
# Warmup Iteration   1: 13.205 ±(99.9%) 0.277 ms/op
Iteration   1: 8.184 ±(99.9%) 0.097 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.184 ms/op


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
# Warmup Iteration   1: 5.142 ±(99.9%) 0.118 ms/op
Iteration   1: 3.000 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.822 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   10.676 ms/op
                 createUser·p0.999:  18.293 ms/op
                 createUser·p0.9999: 19.024 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10736
  mean =      3.000 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2265 
    [ 2.500,  3.750) = 7802 
    [ 3.750,  5.000) = 359 
    [ 5.000,  6.250) = 141 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =     10.676 ms/op
     p(99.9000) =     18.293 ms/op
     p(99.9900) =     19.024 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 3.428 ±(99.9%) 0.083 ms/op
Iteration   1: 1.958 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.478 ms/op
                 existUser·p0.50:   1.966 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   3.153 ms/op
                 existUser·p0.999:  7.924 ms/op
                 existUser·p0.9999: 8.310 ms/op
                 existUser·p1.00:   8.471 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16333
  mean =      1.958 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 21 
    [1.000, 1.500) = 3482 
    [1.500, 2.000) = 5096 
    [2.000, 2.500) = 6040 
    [2.500, 3.000) = 1409 
    [3.000, 3.500) = 195 
    [3.500, 4.000) = 43 
    [4.000, 4.500) = 7 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 28 
    [8.000, 8.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.153 ms/op
     p(99.9000) =      7.924 ms/op
     p(99.9900) =      8.310 ms/op
     p(99.9990) =      8.471 ms/op
     p(99.9999) =      8.471 ms/op
    p(100.0000) =      8.471 ms/op


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
# Warmup Iteration   1: 4.588 ±(99.9%) 0.116 ms/op
Iteration   1: 3.157 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   4.006 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.639 ms/op
                 getUser·p0.999:  14.315 ms/op
                 getUser·p0.9999: 17.676 ms/op
                 getUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10253
  mean =      3.157 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 1634 
    [ 2.500,  3.750) = 7023 
    [ 3.750,  5.000) = 1368 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.639 ms/op
     p(99.9000) =     14.315 ms/op
     p(99.9900) =     17.676 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 12.460 ±(99.9%) 0.552 ms/op
Iteration   1: 8.336 ±(99.9%) 0.122 ms/op
                 listUser·p0.00:   3.273 ms/op
                 listUser·p0.50:   8.020 ms/op
                 listUser·p0.90:   10.666 ms/op
                 listUser·p0.95:   11.846 ms/op
                 listUser·p0.99:   16.936 ms/op
                 listUser·p0.999:  27.647 ms/op
                 listUser·p0.9999: 29.098 ms/op
                 listUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3837
  mean =      8.336 ±(99.9%) 0.122 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 69 
    [ 5.000,  7.500) = 1320 
    [ 7.500, 10.000) = 1865 
    [10.000, 12.500) = 442 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      3.273 ms/op
     p(50.0000) =      8.020 ms/op
     p(90.0000) =     10.666 ms/op
     p(95.0000) =     11.846 ms/op
     p(99.0000) =     16.936 ms/op
     p(99.9000) =     27.647 ms/op
     p(99.9900) =     29.098 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.120          ops/ms
Client.existUser                       thrpt         12.483          ops/ms
Client.getUser                         thrpt          8.471          ops/ms
Client.listUser                        thrpt          3.248          ops/ms
Client.createUser                       avgt          3.030           ms/op
Client.existUser                        avgt          1.810           ms/op
Client.getUser                          avgt          2.703           ms/op
Client.listUser                         avgt          8.184           ms/op
Client.createUser                     sample  10736   3.000 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          1.007           ms/op
Client.createUser:createUser·p0.50    sample          2.822           ms/op
Client.createUser:createUser·p0.90    sample          3.457           ms/op
Client.createUser:createUser·p0.95    sample          3.924           ms/op
Client.createUser:createUser·p0.99    sample         10.676           ms/op
Client.createUser:createUser·p0.999   sample         18.293           ms/op
Client.createUser:createUser·p0.9999  sample         19.024           ms/op
Client.createUser:createUser·p1.00    sample         19.038           ms/op
Client.existUser                      sample  16333   1.958 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.478           ms/op
Client.existUser:existUser·p0.50      sample          1.966           ms/op
Client.existUser:existUser·p0.90      sample          2.507           ms/op
Client.existUser:existUser·p0.95      sample          2.683           ms/op
Client.existUser:existUser·p0.99      sample          3.153           ms/op
Client.existUser:existUser·p0.999     sample          7.924           ms/op
Client.existUser:existUser·p0.9999    sample          8.310           ms/op
Client.existUser:existUser·p1.00      sample          8.471           ms/op
Client.getUser                        sample  10253   3.157 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          0.908           ms/op
Client.getUser:getUser·p0.50          sample          3.039           ms/op
Client.getUser:getUser·p0.90          sample          4.006           ms/op
Client.getUser:getUser·p0.95          sample          4.383           ms/op
Client.getUser:getUser·p0.99          sample          6.639           ms/op
Client.getUser:getUser·p0.999         sample         14.315           ms/op
Client.getUser:getUser·p0.9999        sample         17.676           ms/op
Client.getUser:getUser·p1.00          sample         17.727           ms/op
Client.listUser                       sample   3837   8.336 ± 0.122   ms/op
Client.listUser:listUser·p0.00        sample          3.273           ms/op
Client.listUser:listUser·p0.50        sample          8.020           ms/op
Client.listUser:listUser·p0.90        sample         10.666           ms/op
Client.listUser:listUser·p0.95        sample         11.846           ms/op
Client.listUser:listUser·p0.99        sample         16.936           ms/op
Client.listUser:listUser·p0.999       sample         27.647           ms/op
Client.listUser:listUser·p0.9999      sample         29.098           ms/op
Client.listUser:listUser·p1.00        sample         29.098           ms/op
