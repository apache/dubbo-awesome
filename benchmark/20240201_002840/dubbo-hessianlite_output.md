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
# Warmup Iteration   1: 2.489 ops/ms
Iteration   1: 6.373 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.373 ops/ms


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
# Warmup Iteration   1: 6.143 ops/ms
Iteration   1: 12.881 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.881 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.994 ops/ms
Iteration   1: 9.132 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.132 ops/ms


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
# Warmup Iteration   1: 2.379 ops/ms
Iteration   1: 3.679 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.679 ops/ms


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
# Warmup Iteration   1: 5.106 ±(99.9%) 0.073 ms/op
Iteration   1: 3.517 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.517 ms/op


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
# Warmup Iteration   1: 3.168 ±(99.9%) 0.032 ms/op
Iteration   1: 2.062 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.062 ms/op


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
# Warmup Iteration   1: 4.595 ±(99.9%) 0.066 ms/op
Iteration   1: 3.084 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.084 ms/op


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
# Warmup Iteration   1: 12.954 ±(99.9%) 0.235 ms/op
Iteration   1: 7.871 ±(99.9%) 0.097 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.871 ms/op


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
# Warmup Iteration   1: 4.720 ±(99.9%) 0.104 ms/op
Iteration   1: 2.965 ±(99.9%) 0.058 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   4.335 ms/op
                 createUser·p0.99:   8.200 ms/op
                 createUser·p0.999:  27.008 ms/op
                 createUser·p0.9999: 27.570 ms/op
                 createUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10775
  mean =      2.965 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3763 
    [ 2.500,  5.000) = 6697 
    [ 5.000,  7.500) = 203 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      4.335 ms/op
     p(99.0000) =      8.200 ms/op
     p(99.9000) =     27.008 ms/op
     p(99.9900) =     27.570 ms/op
     p(99.9990) =     27.591 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 2.971 ±(99.9%) 0.064 ms/op
Iteration   1: 1.806 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   1.731 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.495 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  5.915 ms/op
                 existUser·p0.9999: 6.169 ms/op
                 existUser·p1.00:   6.169 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17695
  mean =      1.806 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 148 
    [1.000, 1.500) = 4087 
    [1.500, 2.000) = 8810 
    [2.000, 2.500) = 3777 
    [2.500, 3.000) = 543 
    [3.000, 3.500) = 77 
    [3.500, 4.000) = 101 
    [4.000, 4.500) = 27 
    [4.500, 5.000) = 44 
    [5.000, 5.500) = 17 
    [5.500, 6.000) = 56 
    [6.000, 6.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.495 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      5.915 ms/op
     p(99.9900) =      6.169 ms/op
     p(99.9990) =      6.169 ms/op
     p(99.9999) =      6.169 ms/op
    p(100.0000) =      6.169 ms/op


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
# Warmup Iteration   1: 5.246 ±(99.9%) 0.129 ms/op
Iteration   1: 2.933 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   2.736 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  11.979 ms/op
                 getUser·p0.9999: 15.227 ms/op
                 getUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10921
  mean =      2.933 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 2837 
    [ 2.500,  3.750) = 6980 
    [ 3.750,  5.000) = 960 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      2.736 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     11.979 ms/op
     p(99.9900) =     15.227 ms/op
     p(99.9990) =     15.319 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


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
# Warmup Iteration   1: 11.769 ±(99.9%) 0.399 ms/op
Iteration   1: 8.465 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   3.228 ms/op
                 listUser·p0.50:   8.159 ms/op
                 listUser·p0.90:   10.956 ms/op
                 listUser·p0.95:   12.141 ms/op
                 listUser·p0.99:   17.134 ms/op
                 listUser·p0.999:  20.093 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3802
  mean =      8.465 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 66 
    [ 5.000,  7.500) = 1355 
    [ 7.500, 10.000) = 1596 
    [10.000, 12.500) = 626 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.228 ms/op
     p(50.0000) =      8.159 ms/op
     p(90.0000) =     10.956 ms/op
     p(95.0000) =     12.141 ms/op
     p(99.0000) =     17.134 ms/op
     p(99.9000) =     20.093 ms/op
     p(99.9900) =     20.578 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.373          ops/ms
Client.existUser                       thrpt         12.881          ops/ms
Client.getUser                         thrpt          9.132          ops/ms
Client.listUser                        thrpt          3.679          ops/ms
Client.createUser                       avgt          3.517           ms/op
Client.existUser                        avgt          2.062           ms/op
Client.getUser                          avgt          3.084           ms/op
Client.listUser                         avgt          7.871           ms/op
Client.createUser                     sample  10775   2.965 ± 0.058   ms/op
Client.createUser:createUser·p0.00    sample          1.141           ms/op
Client.createUser:createUser·p0.50    sample          2.671           ms/op
Client.createUser:createUser·p0.90    sample          3.715           ms/op
Client.createUser:createUser·p0.95    sample          4.335           ms/op
Client.createUser:createUser·p0.99    sample          8.200           ms/op
Client.createUser:createUser·p0.999   sample         27.008           ms/op
Client.createUser:createUser·p0.9999  sample         27.570           ms/op
Client.createUser:createUser·p1.00    sample         27.591           ms/op
Client.existUser                      sample  17695   1.806 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.710           ms/op
Client.existUser:existUser·p0.50      sample          1.731           ms/op
Client.existUser:existUser·p0.90      sample          2.290           ms/op
Client.existUser:existUser·p0.95      sample          2.495           ms/op
Client.existUser:existUser·p0.99      sample          3.817           ms/op
Client.existUser:existUser·p0.999     sample          5.915           ms/op
Client.existUser:existUser·p0.9999    sample          6.169           ms/op
Client.existUser:existUser·p1.00      sample          6.169           ms/op
Client.getUser                        sample  10921   2.933 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          1.149           ms/op
Client.getUser:getUser·p0.50          sample          2.736           ms/op
Client.getUser:getUser·p0.90          sample          3.752           ms/op
Client.getUser:getUser·p0.95          sample          4.026           ms/op
Client.getUser:getUser·p0.99          sample          5.382           ms/op
Client.getUser:getUser·p0.999         sample         11.979           ms/op
Client.getUser:getUser·p0.9999        sample         15.227           ms/op
Client.getUser:getUser·p1.00          sample         15.319           ms/op
Client.listUser                       sample   3802   8.465 ± 0.121   ms/op
Client.listUser:listUser·p0.00        sample          3.228           ms/op
Client.listUser:listUser·p0.50        sample          8.159           ms/op
Client.listUser:listUser·p0.90        sample         10.956           ms/op
Client.listUser:listUser·p0.95        sample         12.141           ms/op
Client.listUser:listUser·p0.99        sample         17.134           ms/op
Client.listUser:listUser·p0.999       sample         20.093           ms/op
Client.listUser:listUser·p0.9999      sample         20.578           ms/op
Client.listUser:listUser·p1.00        sample         20.578           ms/op
