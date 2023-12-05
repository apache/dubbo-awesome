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
# Warmup Iteration   1: 2.568 ops/ms
Iteration   1: 6.327 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.327 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 6.478 ops/ms
Iteration   1: 12.814 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.814 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.403 ops/ms
Iteration   1: 8.795 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.795 ops/ms


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
# Warmup Iteration   1: 2.314 ops/ms
Iteration   1: 3.734 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.734 ops/ms


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
# Warmup Iteration   1: 4.872 ±(99.9%) 0.073 ms/op
Iteration   1: 2.658 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.658 ms/op


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
# Warmup Iteration   1: 2.861 ±(99.9%) 0.027 ms/op
Iteration   1: 1.759 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.759 ms/op


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
# Warmup Iteration   1: 4.577 ±(99.9%) 0.058 ms/op
Iteration   1: 2.966 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.966 ms/op


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
# Warmup Iteration   1: 11.498 ±(99.9%) 0.160 ms/op
Iteration   1: 7.560 ±(99.9%) 0.153 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.560 ms/op


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
# Warmup Iteration   1: 4.826 ±(99.9%) 0.134 ms/op
Iteration   1: 3.189 ±(99.9%) 0.069 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   2.802 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   4.810 ms/op
                 createUser·p0.99:   10.699 ms/op
                 createUser·p0.999:  34.406 ms/op
                 createUser·p0.9999: 34.799 ms/op
                 createUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10107
  mean =      3.189 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2172 
    [ 2.500,  5.000) = 7463 
    [ 5.000,  7.500) = 217 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      2.802 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      4.810 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     34.406 ms/op
     p(99.9900) =     34.799 ms/op
     p(99.9990) =     34.800 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 3.080 ±(99.9%) 0.080 ms/op
Iteration   1: 2.005 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   1.968 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.679 ms/op
                 existUser·p0.99:   3.277 ms/op
                 existUser·p0.999:  5.710 ms/op
                 existUser·p0.9999: 5.992 ms/op
                 existUser·p1.00:   6.046 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15984
  mean =      2.005 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 159 
    [1.000, 1.500) = 1464 
    [1.500, 2.000) = 6901 
    [2.000, 2.500) = 5818 
    [2.500, 3.000) = 1416 
    [3.000, 3.500) = 127 
    [3.500, 4.000) = 28 
    [4.000, 4.500) = 32 
    [4.500, 5.000) = 4 
    [5.000, 5.500) = 3 
    [5.500, 6.000) = 31 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      3.277 ms/op
     p(99.9000) =      5.710 ms/op
     p(99.9900) =      5.992 ms/op
     p(99.9990) =      6.046 ms/op
     p(99.9999) =      6.046 ms/op
    p(100.0000) =      6.046 ms/op


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
# Warmup Iteration   1: 4.381 ±(99.9%) 0.092 ms/op
Iteration   1: 3.341 ±(99.9%) 0.158 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   2.806 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.302 ms/op
                 getUser·p0.99:   27.115 ms/op
                 getUser·p0.999:  79.667 ms/op
                 getUser·p0.9999: 80.740 ms/op
                 getUser·p1.00:   80.740 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9595
  mean =      3.341 ±(99.9%) 0.158 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9340 
    [ 5.000, 10.000) = 142 
    [10.000, 15.000) = 6 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 29 
    [30.000, 35.000) = 38 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 2 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 2 
    [65.000, 70.000) = 4 
    [70.000, 75.000) = 5 
    [75.000, 80.000) = 9 
    [80.000, 85.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.302 ms/op
     p(99.0000) =     27.115 ms/op
     p(99.9000) =     79.667 ms/op
     p(99.9900) =     80.740 ms/op
     p(99.9990) =     80.740 ms/op
     p(99.9999) =     80.740 ms/op
    p(100.0000) =     80.740 ms/op


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
# Warmup Iteration   1: 12.090 ±(99.9%) 0.462 ms/op
Iteration   1: 8.265 ±(99.9%) 0.135 ms/op
                 listUser·p0.00:   2.740 ms/op
                 listUser·p0.50:   7.864 ms/op
                 listUser·p0.90:   11.239 ms/op
                 listUser·p0.95:   11.993 ms/op
                 listUser·p0.99:   18.496 ms/op
                 listUser·p0.999:  23.626 ms/op
                 listUser·p0.9999: 29.065 ms/op
                 listUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3990
  mean =      8.265 ±(99.9%) 0.135 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 169 
    [ 5.000,  7.500) = 1485 
    [ 7.500, 10.000) = 1628 
    [10.000, 12.500) = 581 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.740 ms/op
     p(50.0000) =      7.864 ms/op
     p(90.0000) =     11.239 ms/op
     p(95.0000) =     11.993 ms/op
     p(99.0000) =     18.496 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.327          ops/ms
Client.existUser                       thrpt         12.814          ops/ms
Client.getUser                         thrpt          8.795          ops/ms
Client.listUser                        thrpt          3.734          ops/ms
Client.createUser                       avgt          2.658           ms/op
Client.existUser                        avgt          1.759           ms/op
Client.getUser                          avgt          2.966           ms/op
Client.listUser                         avgt          7.560           ms/op
Client.createUser                     sample  10107   3.189 ± 0.069   ms/op
Client.createUser:createUser·p0.00    sample          1.042           ms/op
Client.createUser:createUser·p0.50    sample          2.802           ms/op
Client.createUser:createUser·p0.90    sample          3.686           ms/op
Client.createUser:createUser·p0.95    sample          4.810           ms/op
Client.createUser:createUser·p0.99    sample         10.699           ms/op
Client.createUser:createUser·p0.999   sample         34.406           ms/op
Client.createUser:createUser·p0.9999  sample         34.799           ms/op
Client.createUser:createUser·p1.00    sample         34.800           ms/op
Client.existUser                      sample  15984   2.005 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.663           ms/op
Client.existUser:existUser·p0.50      sample          1.968           ms/op
Client.existUser:existUser·p0.90      sample          2.507           ms/op
Client.existUser:existUser·p0.95      sample          2.679           ms/op
Client.existUser:existUser·p0.99      sample          3.277           ms/op
Client.existUser:existUser·p0.999     sample          5.710           ms/op
Client.existUser:existUser·p0.9999    sample          5.992           ms/op
Client.existUser:existUser·p1.00      sample          6.046           ms/op
Client.getUser                        sample   9595   3.341 ± 0.158   ms/op
Client.getUser:getUser·p0.00          sample          0.593           ms/op
Client.getUser:getUser·p0.50          sample          2.806           ms/op
Client.getUser:getUser·p0.90          sample          3.895           ms/op
Client.getUser:getUser·p0.95          sample          4.302           ms/op
Client.getUser:getUser·p0.99          sample         27.115           ms/op
Client.getUser:getUser·p0.999         sample         79.667           ms/op
Client.getUser:getUser·p0.9999        sample         80.740           ms/op
Client.getUser:getUser·p1.00          sample         80.740           ms/op
Client.listUser                       sample   3990   8.265 ± 0.135   ms/op
Client.listUser:listUser·p0.00        sample          2.740           ms/op
Client.listUser:listUser·p0.50        sample          7.864           ms/op
Client.listUser:listUser·p0.90        sample         11.239           ms/op
Client.listUser:listUser·p0.95        sample         11.993           ms/op
Client.listUser:listUser·p0.99        sample         18.496           ms/op
Client.listUser:listUser·p0.999       sample         23.626           ms/op
Client.listUser:listUser·p0.9999      sample         29.065           ms/op
Client.listUser:listUser·p1.00        sample         29.065           ms/op
