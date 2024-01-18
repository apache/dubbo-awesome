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
# Warmup Iteration   1: 2.160 ops/ms
Iteration   1: 5.277 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.277 ops/ms


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
# Warmup Iteration   1: 6.841 ops/ms
Iteration   1: 12.413 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.413 ops/ms


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
# Warmup Iteration   1: 3.745 ops/ms
Iteration   1: 7.499 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.499 ops/ms


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
# Warmup Iteration   1: 2.234 ops/ms
Iteration   1: 3.844 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.844 ops/ms


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
# Warmup Iteration   1: 5.483 ±(99.9%) 0.099 ms/op
Iteration   1: 3.136 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.136 ms/op


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
# Warmup Iteration   1: 3.241 ±(99.9%) 0.038 ms/op
Iteration   1: 1.907 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.907 ms/op


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
# Warmup Iteration   1: 4.709 ±(99.9%) 0.074 ms/op
Iteration   1: 2.870 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.870 ms/op


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
# Warmup Iteration   1: 11.343 ±(99.9%) 0.208 ms/op
Iteration   1: 8.597 ±(99.9%) 0.216 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.597 ms/op


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
# Warmup Iteration   1: 5.024 ±(99.9%) 0.096 ms/op
Iteration   1: 3.058 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.851 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   7.959 ms/op
                 createUser·p0.999:  21.561 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10445
  mean =      3.058 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3657 
    [ 2.500,  5.000) = 6516 
    [ 5.000,  7.500) = 146 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      7.959 ms/op
     p(99.9000) =     21.561 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.065 ms/op
Iteration   1: 1.820 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   1.790 ms/op
                 existUser·p0.90:   2.363 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   3.895 ms/op
                 existUser·p0.999:  7.581 ms/op
                 existUser·p0.9999: 7.771 ms/op
                 existUser·p1.00:   7.840 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17577
  mean =      1.820 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 219 
    [1.000, 1.500) = 4969 
    [1.500, 2.000) = 6788 
    [2.000, 2.500) = 4647 
    [2.500, 3.000) = 646 
    [3.000, 3.500) = 92 
    [3.500, 4.000) = 45 
    [4.000, 4.500) = 15 
    [4.500, 5.000) = 35 
    [5.000, 5.500) = 25 
    [5.500, 6.000) = 38 
    [6.000, 6.500) = 12 
    [6.500, 7.000) = 21 
    [7.000, 7.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.790 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      7.581 ms/op
     p(99.9900) =      7.771 ms/op
     p(99.9990) =      7.840 ms/op
     p(99.9999) =      7.840 ms/op
    p(100.0000) =      7.840 ms/op


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
# Warmup Iteration   1: 4.468 ±(99.9%) 0.096 ms/op
Iteration   1: 2.961 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.851 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.890 ms/op
                 getUser·p0.99:   4.635 ms/op
                 getUser·p0.999:  23.265 ms/op
                 getUser·p0.9999: 23.421 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10824
  mean =      2.961 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2868 
    [ 2.500,  5.000) = 7876 
    [ 5.000,  7.500) = 45 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.890 ms/op
     p(99.0000) =      4.635 ms/op
     p(99.9000) =     23.265 ms/op
     p(99.9900) =     23.421 ms/op
     p(99.9990) =     23.429 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 12.949 ±(99.9%) 0.669 ms/op
Iteration   1: 7.897 ±(99.9%) 0.160 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   7.340 ms/op
                 listUser·p0.90:   10.212 ms/op
                 listUser·p0.95:   11.780 ms/op
                 listUser·p0.99:   20.467 ms/op
                 listUser·p0.999:  31.820 ms/op
                 listUser·p0.9999: 50.856 ms/op
                 listUser·p1.00:   50.856 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4046
  mean =      7.897 ±(99.9%) 0.160 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 173 
    [ 5.000, 10.000) = 3428 
    [10.000, 15.000) = 343 
    [15.000, 20.000) = 59 
    [20.000, 25.000) = 10 
    [25.000, 30.000) = 26 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      7.340 ms/op
     p(90.0000) =     10.212 ms/op
     p(95.0000) =     11.780 ms/op
     p(99.0000) =     20.467 ms/op
     p(99.9000) =     31.820 ms/op
     p(99.9900) =     50.856 ms/op
     p(99.9990) =     50.856 ms/op
     p(99.9999) =     50.856 ms/op
    p(100.0000) =     50.856 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.277          ops/ms
Client.existUser                       thrpt         12.413          ops/ms
Client.getUser                         thrpt          7.499          ops/ms
Client.listUser                        thrpt          3.844          ops/ms
Client.createUser                       avgt          3.136           ms/op
Client.existUser                        avgt          1.907           ms/op
Client.getUser                          avgt          2.870           ms/op
Client.listUser                         avgt          8.597           ms/op
Client.createUser                     sample  10445   3.058 ± 0.053   ms/op
Client.createUser:createUser·p0.00    sample          1.079           ms/op
Client.createUser:createUser·p0.50    sample          2.851           ms/op
Client.createUser:createUser·p0.90    sample          3.850           ms/op
Client.createUser:createUser·p0.95    sample          4.178           ms/op
Client.createUser:createUser·p0.99    sample          7.959           ms/op
Client.createUser:createUser·p0.999   sample         21.561           ms/op
Client.createUser:createUser·p0.9999  sample         21.660           ms/op
Client.createUser:createUser·p1.00    sample         21.660           ms/op
Client.existUser                      sample  17577   1.820 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.564           ms/op
Client.existUser:existUser·p0.50      sample          1.790           ms/op
Client.existUser:existUser·p0.90      sample          2.363           ms/op
Client.existUser:existUser·p0.95      sample          2.523           ms/op
Client.existUser:existUser·p0.99      sample          3.895           ms/op
Client.existUser:existUser·p0.999     sample          7.581           ms/op
Client.existUser:existUser·p0.9999    sample          7.771           ms/op
Client.existUser:existUser·p1.00      sample          7.840           ms/op
Client.getUser                        sample  10824   2.961 ± 0.040   ms/op
Client.getUser:getUser·p0.00          sample          0.868           ms/op
Client.getUser:getUser·p0.50          sample          2.851           ms/op
Client.getUser:getUser·p0.90          sample          3.658           ms/op
Client.getUser:getUser·p0.95          sample          3.890           ms/op
Client.getUser:getUser·p0.99          sample          4.635           ms/op
Client.getUser:getUser·p0.999         sample         23.265           ms/op
Client.getUser:getUser·p0.9999        sample         23.421           ms/op
Client.getUser:getUser·p1.00          sample         23.429           ms/op
Client.listUser                       sample   4046   7.897 ± 0.160   ms/op
Client.listUser:listUser·p0.00        sample          1.438           ms/op
Client.listUser:listUser·p0.50        sample          7.340           ms/op
Client.listUser:listUser·p0.90        sample         10.212           ms/op
Client.listUser:listUser·p0.95        sample         11.780           ms/op
Client.listUser:listUser·p0.99        sample         20.467           ms/op
Client.listUser:listUser·p0.999       sample         31.820           ms/op
Client.listUser:listUser·p0.9999      sample         50.856           ms/op
Client.listUser:listUser·p1.00        sample         50.856           ms/op
