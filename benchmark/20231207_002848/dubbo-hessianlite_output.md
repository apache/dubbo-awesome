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
# Warmup Iteration   1: 2.163 ops/ms
Iteration   1: 5.894 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.894 ops/ms


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
# Warmup Iteration   1: 6.036 ops/ms
Iteration   1: 12.159 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.159 ops/ms


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
# Warmup Iteration   1: 3.852 ops/ms
Iteration   1: 8.112 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.112 ops/ms


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
# Warmup Iteration   1: 2.159 ops/ms
Iteration   1: 3.971 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.971 ops/ms


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
# Warmup Iteration   1: 5.361 ±(99.9%) 0.063 ms/op
Iteration   1: 3.062 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.062 ms/op


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
# Warmup Iteration   1: 3.344 ±(99.9%) 0.032 ms/op
Iteration   1: 2.029 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.029 ms/op


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
# Warmup Iteration   1: 5.685 ±(99.9%) 0.078 ms/op
Iteration   1: 3.543 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.543 ms/op


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
# Warmup Iteration   1: 13.732 ±(99.9%) 0.255 ms/op
Iteration   1: 9.171 ±(99.9%) 0.115 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.171 ms/op


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
# Warmup Iteration   1: 5.016 ±(99.9%) 0.116 ms/op
Iteration   1: 3.202 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.247 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.827 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  9.160 ms/op
                 createUser·p0.9999: 10.043 ms/op
                 createUser·p1.00:   10.043 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9985
  mean =      3.202 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 149 
    [ 2.000,  3.000) = 3749 
    [ 3.000,  4.000) = 5404 
    [ 4.000,  5.000) = 525 
    [ 5.000,  6.000) = 82 
    [ 6.000,  7.000) = 5 
    [ 7.000,  8.000) = 23 
    [ 8.000,  9.000) = 36 
    [ 9.000, 10.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.827 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =      9.160 ms/op
     p(99.9900) =     10.043 ms/op
     p(99.9990) =     10.043 ms/op
     p(99.9999) =     10.043 ms/op
    p(100.0000) =     10.043 ms/op


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
# Warmup Iteration   1: 2.876 ±(99.9%) 0.061 ms/op
Iteration   1: 1.617 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   1.559 ms/op
                 existUser·p0.90:   1.873 ms/op
                 existUser·p0.95:   2.021 ms/op
                 existUser·p0.99:   2.405 ms/op
                 existUser·p0.999:  30.835 ms/op
                 existUser·p0.9999: 31.130 ms/op
                 existUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19793
  mean =      1.617 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19626 
    [ 2.500,  5.000) = 106 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      1.559 ms/op
     p(90.0000) =      1.873 ms/op
     p(95.0000) =      2.021 ms/op
     p(99.0000) =      2.405 ms/op
     p(99.9000) =     30.835 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     31.162 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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
# Warmup Iteration   1: 4.821 ±(99.9%) 0.130 ms/op
Iteration   1: 3.126 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   5.994 ms/op
                 getUser·p0.999:  8.034 ms/op
                 getUser·p0.9999: 9.715 ms/op
                 getUser·p1.00:   9.716 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10228
  mean =      3.126 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 5 
    [ 1.000,  2.000) = 458 
    [ 2.000,  3.000) = 3933 
    [ 3.000,  4.000) = 5108 
    [ 4.000,  5.000) = 593 
    [ 5.000,  6.000) = 30 
    [ 6.000,  7.000) = 26 
    [ 7.000,  8.000) = 57 
    [ 8.000,  9.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.994 ms/op
     p(99.9000) =      8.034 ms/op
     p(99.9900) =      9.715 ms/op
     p(99.9990) =      9.716 ms/op
     p(99.9999) =      9.716 ms/op
    p(100.0000) =      9.716 ms/op


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
# Warmup Iteration   1: 13.465 ±(99.9%) 0.452 ms/op
Iteration   1: 8.615 ±(99.9%) 0.141 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   8.143 ms/op
                 listUser·p0.90:   11.780 ms/op
                 listUser·p0.95:   12.979 ms/op
                 listUser·p0.99:   16.543 ms/op
                 listUser·p0.999:  27.449 ms/op
                 listUser·p0.9999: 31.097 ms/op
                 listUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3715
  mean =      8.615 ±(99.9%) 0.141 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 90 
    [ 5.000,  7.500) = 1297 
    [ 7.500, 10.000) = 1499 
    [10.000, 12.500) = 591 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.617 ms/op
     p(50.0000) =      8.143 ms/op
     p(90.0000) =     11.780 ms/op
     p(95.0000) =     12.979 ms/op
     p(99.0000) =     16.543 ms/op
     p(99.9000) =     27.449 ms/op
     p(99.9900) =     31.097 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.894          ops/ms
Client.existUser                       thrpt         12.159          ops/ms
Client.getUser                         thrpt          8.112          ops/ms
Client.listUser                        thrpt          3.971          ops/ms
Client.createUser                       avgt          3.062           ms/op
Client.existUser                        avgt          2.029           ms/op
Client.getUser                          avgt          3.543           ms/op
Client.listUser                         avgt          9.171           ms/op
Client.createUser                     sample   9985   3.202 ± 0.023   ms/op
Client.createUser:createUser·p0.00    sample          1.247           ms/op
Client.createUser:createUser·p0.50    sample          3.113           ms/op
Client.createUser:createUser·p0.90    sample          3.827           ms/op
Client.createUser:createUser·p0.95    sample          4.145           ms/op
Client.createUser:createUser·p0.99    sample          5.767           ms/op
Client.createUser:createUser·p0.999   sample          9.160           ms/op
Client.createUser:createUser·p0.9999  sample         10.043           ms/op
Client.createUser:createUser·p1.00    sample         10.043           ms/op
Client.existUser                      sample  19793   1.617 ± 0.028   ms/op
Client.existUser:existUser·p0.00      sample          0.531           ms/op
Client.existUser:existUser·p0.50      sample          1.559           ms/op
Client.existUser:existUser·p0.90      sample          1.873           ms/op
Client.existUser:existUser·p0.95      sample          2.021           ms/op
Client.existUser:existUser·p0.99      sample          2.405           ms/op
Client.existUser:existUser·p0.999     sample         30.835           ms/op
Client.existUser:existUser·p0.9999    sample         31.130           ms/op
Client.existUser:existUser·p1.00      sample         31.162           ms/op
Client.getUser                        sample  10228   3.126 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.601           ms/op
Client.getUser:getUser·p0.50          sample          3.129           ms/op
Client.getUser:getUser·p0.90          sample          3.883           ms/op
Client.getUser:getUser·p0.95          sample          4.129           ms/op
Client.getUser:getUser·p0.99          sample          5.994           ms/op
Client.getUser:getUser·p0.999         sample          8.034           ms/op
Client.getUser:getUser·p0.9999        sample          9.715           ms/op
Client.getUser:getUser·p1.00          sample          9.716           ms/op
Client.listUser                       sample   3715   8.615 ± 0.141   ms/op
Client.listUser:listUser·p0.00        sample          2.617           ms/op
Client.listUser:listUser·p0.50        sample          8.143           ms/op
Client.listUser:listUser·p0.90        sample         11.780           ms/op
Client.listUser:listUser·p0.95        sample         12.979           ms/op
Client.listUser:listUser·p0.99        sample         16.543           ms/op
Client.listUser:listUser·p0.999       sample         27.449           ms/op
Client.listUser:listUser·p0.9999      sample         31.097           ms/op
Client.listUser:listUser·p1.00        sample         31.097           ms/op
