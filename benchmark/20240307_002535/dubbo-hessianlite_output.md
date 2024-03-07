# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.320 ops/ms
Iteration   1: 6.189 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.189 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.184 ops/ms
Iteration   1: 12.071 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.071 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.282 ops/ms
Iteration   1: 7.882 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.882 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.173 ops/ms
Iteration   1: 3.512 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.512 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.387 ±(99.9%) 0.063 ms/op
Iteration   1: 3.156 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.156 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.124 ±(99.9%) 0.033 ms/op
Iteration   1: 2.085 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.085 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.886 ±(99.9%) 0.052 ms/op
Iteration   1: 3.032 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.032 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 14.806 ±(99.9%) 0.296 ms/op
Iteration   1: 9.854 ±(99.9%) 0.110 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.854 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.968 ±(99.9%) 0.123 ms/op
Iteration   1: 3.521 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   5.382 ms/op
                 createUser·p0.99:   6.784 ms/op
                 createUser·p0.999:  17.465 ms/op
                 createUser·p0.9999: 17.596 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9085
  mean =      3.521 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 392 
    [ 2.500,  3.750) = 6418 
    [ 3.750,  5.000) = 1732 
    [ 5.000,  6.250) = 355 
    [ 6.250,  7.500) = 152 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.382 ms/op
     p(99.0000) =      6.784 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.203 ±(99.9%) 0.085 ms/op
Iteration   1: 1.593 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   1.495 ms/op
                 existUser·p0.90:   2.093 ms/op
                 existUser·p0.95:   2.392 ms/op
                 existUser·p0.99:   2.847 ms/op
                 existUser·p0.999:  5.578 ms/op
                 existUser·p0.9999: 8.052 ms/op
                 existUser·p1.00:   8.094 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 20060
  mean =      1.593 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 116 
    [1.000, 1.500) = 10104 
    [1.500, 2.000) = 7333 
    [2.000, 2.500) = 1835 
    [2.500, 3.000) = 539 
    [3.000, 3.500) = 91 
    [3.500, 4.000) = 7 
    [4.000, 4.500) = 3 
    [4.500, 5.000) = 0 
    [5.000, 5.500) = 6 
    [5.500, 6.000) = 7 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 6 
    [7.000, 7.500) = 6 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      1.495 ms/op
     p(90.0000) =      2.093 ms/op
     p(95.0000) =      2.392 ms/op
     p(99.0000) =      2.847 ms/op
     p(99.9000) =      5.578 ms/op
     p(99.9900) =      8.052 ms/op
     p(99.9990) =      8.094 ms/op
     p(99.9999) =      8.094 ms/op
    p(100.0000) =      8.094 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.614 ±(99.9%) 0.112 ms/op
Iteration   1: 2.956 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   2.859 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  6.235 ms/op
                 getUser·p0.9999: 7.967 ms/op
                 getUser·p1.00:   7.987 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10815
  mean =      2.956 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 5 
    [1.000, 1.500) = 28 
    [1.500, 2.000) = 192 
    [2.000, 2.500) = 2789 
    [2.500, 3.000) = 3239 
    [3.000, 3.500) = 2486 
    [3.500, 4.000) = 1491 
    [4.000, 4.500) = 427 
    [4.500, 5.000) = 64 
    [5.000, 5.500) = 29 
    [5.500, 6.000) = 43 
    [6.000, 6.500) = 13 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.850 ms/op
     p(99.9000) =      6.235 ms/op
     p(99.9900) =      7.967 ms/op
     p(99.9990) =      7.987 ms/op
     p(99.9999) =      7.987 ms/op
    p(100.0000) =      7.987 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.297 ±(99.9%) 0.476 ms/op
Iteration   1: 8.349 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   3.084 ms/op
                 listUser·p0.50:   8.102 ms/op
                 listUser·p0.90:   10.784 ms/op
                 listUser·p0.95:   11.911 ms/op
                 listUser·p0.99:   16.237 ms/op
                 listUser·p0.999:  20.862 ms/op
                 listUser·p0.9999: 31.261 ms/op
                 listUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3817
  mean =      8.349 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 118 
    [ 5.000,  7.500) = 1257 
    [ 7.500, 10.000) = 1821 
    [10.000, 12.500) = 490 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.084 ms/op
     p(50.0000) =      8.102 ms/op
     p(90.0000) =     10.784 ms/op
     p(95.0000) =     11.911 ms/op
     p(99.0000) =     16.237 ms/op
     p(99.9000) =     20.862 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     31.261 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.189          ops/ms
Client.existUser                       thrpt         12.071          ops/ms
Client.getUser                         thrpt          7.882          ops/ms
Client.listUser                        thrpt          3.512          ops/ms
Client.createUser                       avgt          3.156           ms/op
Client.existUser                        avgt          2.085           ms/op
Client.getUser                          avgt          3.032           ms/op
Client.listUser                         avgt          9.854           ms/op
Client.createUser                     sample   9085   3.521 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.192           ms/op
Client.createUser:createUser·p0.50    sample          3.293           ms/op
Client.createUser:createUser·p0.90    sample          4.514           ms/op
Client.createUser:createUser·p0.95    sample          5.382           ms/op
Client.createUser:createUser·p0.99    sample          6.784           ms/op
Client.createUser:createUser·p0.999   sample         17.465           ms/op
Client.createUser:createUser·p0.9999  sample         17.596           ms/op
Client.createUser:createUser·p1.00    sample         17.596           ms/op
Client.existUser                      sample  20060   1.593 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.631           ms/op
Client.existUser:existUser·p0.50      sample          1.495           ms/op
Client.existUser:existUser·p0.90      sample          2.093           ms/op
Client.existUser:existUser·p0.95      sample          2.392           ms/op
Client.existUser:existUser·p0.99      sample          2.847           ms/op
Client.existUser:existUser·p0.999     sample          5.578           ms/op
Client.existUser:existUser·p0.9999    sample          8.052           ms/op
Client.existUser:existUser·p1.00      sample          8.094           ms/op
Client.getUser                        sample  10815   2.956 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.821           ms/op
Client.getUser:getUser·p0.50          sample          2.859           ms/op
Client.getUser:getUser·p0.90          sample          3.785           ms/op
Client.getUser:getUser·p0.95          sample          4.026           ms/op
Client.getUser:getUser·p0.99          sample          4.850           ms/op
Client.getUser:getUser·p0.999         sample          6.235           ms/op
Client.getUser:getUser·p0.9999        sample          7.967           ms/op
Client.getUser:getUser·p1.00          sample          7.987           ms/op
Client.listUser                       sample   3817   8.349 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          3.084           ms/op
Client.listUser:listUser·p0.50        sample          8.102           ms/op
Client.listUser:listUser·p0.90        sample         10.784           ms/op
Client.listUser:listUser·p0.95        sample         11.911           ms/op
Client.listUser:listUser·p0.99        sample         16.237           ms/op
Client.listUser:listUser·p0.999       sample         20.862           ms/op
Client.listUser:listUser·p0.9999      sample         31.261           ms/op
Client.listUser:listUser·p1.00        sample         31.261           ms/op
