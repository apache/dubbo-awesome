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
# Warmup Iteration   1: 2.522 ops/ms
Iteration   1: 6.123 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.123 ops/ms


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
# Warmup Iteration   1: 6.295 ops/ms
Iteration   1: 9.472 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.472 ops/ms


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
# Warmup Iteration   1: 5.120 ops/ms
Iteration   1: 8.477 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.477 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.081 ops/ms
Iteration   1: 3.905 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.905 ops/ms


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
# Warmup Iteration   1: 5.332 ±(99.9%) 0.075 ms/op
Iteration   1: 3.271 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.271 ms/op


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
# Warmup Iteration   1: 3.146 ±(99.9%) 0.039 ms/op
Iteration   1: 1.796 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.796 ms/op


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
# Warmup Iteration   1: 5.333 ±(99.9%) 0.069 ms/op
Iteration   1: 3.067 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.067 ms/op


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
# Warmup Iteration   1: 11.474 ±(99.9%) 0.207 ms/op
Iteration   1: 8.780 ±(99.9%) 0.112 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.780 ms/op


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
# Warmup Iteration   1: 4.902 ±(99.9%) 0.101 ms/op
Iteration   1: 2.901 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   2.691 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   6.470 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11260
  mean =      2.901 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 3222 
    [ 2.500,  3.750) = 7164 
    [ 3.750,  5.000) = 679 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      2.691 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      6.470 ms/op
     p(99.9000) =     18.743 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 3.167 ±(99.9%) 0.088 ms/op
Iteration   1: 1.841 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   3.117 ms/op
                 existUser·p0.999:  4.330 ms/op
                 existUser·p0.9999: 6.245 ms/op
                 existUser·p1.00:   6.275 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17378
  mean =      1.841 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 74 
    [1.000, 1.500) = 3078 
    [1.500, 2.000) = 8586 
    [2.000, 2.500) = 4938 
    [2.500, 3.000) = 483 
    [3.000, 3.500) = 152 
    [3.500, 4.000) = 37 
    [4.000, 4.500) = 15 
    [4.500, 5.000) = 2 
    [5.000, 5.500) = 5 
    [5.500, 6.000) = 6 
    [6.000, 6.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.117 ms/op
     p(99.9000) =      4.330 ms/op
     p(99.9900) =      6.245 ms/op
     p(99.9990) =      6.275 ms/op
     p(99.9999) =      6.275 ms/op
    p(100.0000) =      6.275 ms/op


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.106 ms/op
Iteration   1: 2.956 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   2.728 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   5.585 ms/op
                 getUser·p0.999:  14.748 ms/op
                 getUser·p0.9999: 15.102 ms/op
                 getUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10831
  mean =      2.956 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 4086 
    [ 2.500,  3.750) = 5470 
    [ 3.750,  5.000) = 1058 
    [ 5.000,  6.250) = 134 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      2.728 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.585 ms/op
     p(99.9000) =     14.748 ms/op
     p(99.9900) =     15.102 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 11.921 ±(99.9%) 0.495 ms/op
Iteration   1: 7.915 ±(99.9%) 0.132 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   7.389 ms/op
                 listUser·p0.90:   10.977 ms/op
                 listUser·p0.95:   12.288 ms/op
                 listUser·p0.99:   19.651 ms/op
                 listUser·p0.999:  22.205 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4028
  mean =      7.915 ±(99.9%) 0.132 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 159 
    [ 5.000,  7.500) = 1986 
    [ 7.500, 10.000) = 1262 
    [10.000, 12.500) = 440 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      7.389 ms/op
     p(90.0000) =     10.977 ms/op
     p(95.0000) =     12.288 ms/op
     p(99.0000) =     19.651 ms/op
     p(99.9000) =     22.205 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.123          ops/ms
Client.existUser                       thrpt          9.472          ops/ms
Client.getUser                         thrpt          8.477          ops/ms
Client.listUser                        thrpt          3.905          ops/ms
Client.createUser                       avgt          3.271           ms/op
Client.existUser                        avgt          1.796           ms/op
Client.getUser                          avgt          3.067           ms/op
Client.listUser                         avgt          8.780           ms/op
Client.createUser                     sample  11260   2.901 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          1.233           ms/op
Client.createUser:createUser·p0.50    sample          2.691           ms/op
Client.createUser:createUser·p0.90    sample          3.584           ms/op
Client.createUser:createUser·p0.95    sample          3.924           ms/op
Client.createUser:createUser·p0.99    sample          6.470           ms/op
Client.createUser:createUser·p0.999   sample         18.743           ms/op
Client.createUser:createUser·p0.9999  sample         18.776           ms/op
Client.createUser:createUser·p1.00    sample         18.776           ms/op
Client.existUser                      sample  17378   1.841 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.581           ms/op
Client.existUser:existUser·p0.50      sample          1.810           ms/op
Client.existUser:existUser·p0.90      sample          2.310           ms/op
Client.existUser:existUser·p0.95      sample          2.458           ms/op
Client.existUser:existUser·p0.99      sample          3.117           ms/op
Client.existUser:existUser·p0.999     sample          4.330           ms/op
Client.existUser:existUser·p0.9999    sample          6.245           ms/op
Client.existUser:existUser·p1.00      sample          6.275           ms/op
Client.getUser                        sample  10831   2.956 ± 0.030   ms/op
Client.getUser:getUser·p0.00          sample          1.063           ms/op
Client.getUser:getUser·p0.50          sample          2.728           ms/op
Client.getUser:getUser·p0.90          sample          3.813           ms/op
Client.getUser:getUser·p0.95          sample          4.088           ms/op
Client.getUser:getUser·p0.99          sample          5.585           ms/op
Client.getUser:getUser·p0.999         sample         14.748           ms/op
Client.getUser:getUser·p0.9999        sample         15.102           ms/op
Client.getUser:getUser·p1.00          sample         15.106           ms/op
Client.listUser                       sample   4028   7.915 ± 0.132   ms/op
Client.listUser:listUser·p0.00        sample          1.534           ms/op
Client.listUser:listUser·p0.50        sample          7.389           ms/op
Client.listUser:listUser·p0.90        sample         10.977           ms/op
Client.listUser:listUser·p0.95        sample         12.288           ms/op
Client.listUser:listUser·p0.99        sample         19.651           ms/op
Client.listUser:listUser·p0.999       sample         22.205           ms/op
Client.listUser:listUser·p0.9999      sample         23.200           ms/op
Client.listUser:listUser·p1.00        sample         23.200           ms/op
