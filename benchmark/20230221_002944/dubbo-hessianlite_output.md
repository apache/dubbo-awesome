# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.437 ops/ms
Iteration   1: 1.099 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.099 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 1.637 ops/ms
Iteration   1: 3.119 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.119 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.091 ops/ms
Iteration   1: 2.206 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.206 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 0.507 ops/ms
Iteration   1: 0.737 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.737 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 32.430 ±(99.9%) 0.574 ms/op
Iteration   1: 18.221 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  18.221 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 22.190 ±(99.9%) 0.367 ms/op
Iteration   1: 12.014 ±(99.9%) 0.097 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.014 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:46
# Fork: 1 of 1
# Warmup Iteration   1: 22.070 ±(99.9%) 0.347 ms/op
Iteration   1: 9.933 ±(99.9%) 0.111 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.933 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 44.600 ±(99.9%) 1.208 ms/op
Iteration   1: 27.825 ±(99.9%) 0.204 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  27.825 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 21.877 ±(99.9%) 0.781 ms/op
Iteration   1: 11.493 ±(99.9%) 0.351 ms/op
                 createUser·p0.00:   4.276 ms/op
                 createUser·p0.50:   10.813 ms/op
                 createUser·p0.90:   17.531 ms/op
                 createUser·p0.95:   22.905 ms/op
                 createUser·p0.99:   34.754 ms/op
                 createUser·p0.999:  36.912 ms/op
                 createUser·p0.9999: 38.011 ms/op
                 createUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2769
  mean =     11.493 ±(99.9%) 0.351 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 2 
    [ 5.000,  7.500) = 653 
    [ 7.500, 10.000) = 616 
    [10.000, 12.500) = 774 
    [12.500, 15.000) = 385 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      4.276 ms/op
     p(50.0000) =     10.813 ms/op
     p(90.0000) =     17.531 ms/op
     p(95.0000) =     22.905 ms/op
     p(99.0000) =     34.754 ms/op
     p(99.9000) =     36.912 ms/op
     p(99.9900) =     38.011 ms/op
     p(99.9990) =     38.011 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.201 ±(99.9%) 0.872 ms/op
Iteration   1: 7.545 ±(99.9%) 0.164 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   6.939 ms/op
                 existUser·p0.90:   10.682 ms/op
                 existUser·p0.95:   13.759 ms/op
                 existUser·p0.99:   24.609 ms/op
                 existUser·p0.999:  27.378 ms/op
                 existUser·p0.9999: 28.770 ms/op
                 existUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4243
  mean =      7.545 ±(99.9%) 0.164 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 465 
    [ 5.000,  7.500) = 2343 
    [ 7.500, 10.000) = 976 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.739 ms/op
     p(50.0000) =      6.939 ms/op
     p(90.0000) =     10.682 ms/op
     p(95.0000) =     13.759 ms/op
     p(99.0000) =     24.609 ms/op
     p(99.9000) =     27.378 ms/op
     p(99.9900) =     28.770 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 19.290 ±(99.9%) 0.673 ms/op
Iteration   1: 7.940 ±(99.9%) 0.155 ms/op
                 getUser·p0.00:   2.388 ms/op
                 getUser·p0.50:   7.209 ms/op
                 getUser·p0.90:   10.584 ms/op
                 getUser·p0.95:   12.655 ms/op
                 getUser·p0.99:   20.611 ms/op
                 getUser·p0.999:  31.096 ms/op
                 getUser·p0.9999: 31.195 ms/op
                 getUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4023
  mean =      7.940 ±(99.9%) 0.155 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 155 
    [ 5.000,  7.500) = 2164 
    [ 7.500, 10.000) = 1172 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.388 ms/op
     p(50.0000) =      7.209 ms/op
     p(90.0000) =     10.584 ms/op
     p(95.0000) =     12.655 ms/op
     p(99.0000) =     20.611 ms/op
     p(99.9000) =     31.096 ms/op
     p(99.9900) =     31.195 ms/op
     p(99.9990) =     31.195 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 37.484 ±(99.9%) 1.284 ms/op
Iteration   1: 26.571 ±(99.9%) 0.543 ms/op
                 listUser·p0.00:   10.486 ms/op
                 listUser·p0.50:   25.395 ms/op
                 listUser·p0.90:   34.669 ms/op
                 listUser·p0.95:   36.477 ms/op
                 listUser·p0.99:   43.445 ms/op
                 listUser·p0.999:  44.485 ms/op
                 listUser·p0.9999: 44.499 ms/op
                 listUser·p1.00:   44.499 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1207
  mean =     26.571 ±(99.9%) 0.543 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 330 
    [25.000, 27.500) = 186 
    [27.500, 30.000) = 138 
    [30.000, 32.500) = 129 
    [32.500, 35.000) = 88 
    [35.000, 37.500) = 61 
    [37.500, 40.000) = 16 
    [40.000, 42.500) = 8 
    [42.500, 45.000) = 17 
    [45.000, 47.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =     10.486 ms/op
     p(50.0000) =     25.395 ms/op
     p(90.0000) =     34.669 ms/op
     p(95.0000) =     36.477 ms/op
     p(99.0000) =     43.445 ms/op
     p(99.9000) =     44.485 ms/op
     p(99.9900) =     44.499 ms/op
     p(99.9990) =     44.499 ms/op
     p(99.9999) =     44.499 ms/op
    p(100.0000) =     44.499 ms/op


# Run complete. Total time: 00:01:34

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.099          ops/ms
Client.existUser                       thrpt         3.119          ops/ms
Client.getUser                         thrpt         2.206          ops/ms
Client.listUser                        thrpt         0.737          ops/ms
Client.createUser                       avgt        18.221           ms/op
Client.existUser                        avgt        12.014           ms/op
Client.getUser                          avgt         9.933           ms/op
Client.listUser                         avgt        27.825           ms/op
Client.createUser                     sample  2769  11.493 ± 0.351   ms/op
Client.createUser:createUser·p0.00    sample         4.276           ms/op
Client.createUser:createUser·p0.50    sample        10.813           ms/op
Client.createUser:createUser·p0.90    sample        17.531           ms/op
Client.createUser:createUser·p0.95    sample        22.905           ms/op
Client.createUser:createUser·p0.99    sample        34.754           ms/op
Client.createUser:createUser·p0.999   sample        36.912           ms/op
Client.createUser:createUser·p0.9999  sample        38.011           ms/op
Client.createUser:createUser·p1.00    sample        38.011           ms/op
Client.existUser                      sample  4243   7.545 ± 0.164   ms/op
Client.existUser:existUser·p0.00      sample         1.739           ms/op
Client.existUser:existUser·p0.50      sample         6.939           ms/op
Client.existUser:existUser·p0.90      sample        10.682           ms/op
Client.existUser:existUser·p0.95      sample        13.759           ms/op
Client.existUser:existUser·p0.99      sample        24.609           ms/op
Client.existUser:existUser·p0.999     sample        27.378           ms/op
Client.existUser:existUser·p0.9999    sample        28.770           ms/op
Client.existUser:existUser·p1.00      sample        28.770           ms/op
Client.getUser                        sample  4023   7.940 ± 0.155   ms/op
Client.getUser:getUser·p0.00          sample         2.388           ms/op
Client.getUser:getUser·p0.50          sample         7.209           ms/op
Client.getUser:getUser·p0.90          sample        10.584           ms/op
Client.getUser:getUser·p0.95          sample        12.655           ms/op
Client.getUser:getUser·p0.99          sample        20.611           ms/op
Client.getUser:getUser·p0.999         sample        31.096           ms/op
Client.getUser:getUser·p0.9999        sample        31.195           ms/op
Client.getUser:getUser·p1.00          sample        31.195           ms/op
Client.listUser                       sample  1207  26.571 ± 0.543   ms/op
Client.listUser:listUser·p0.00        sample        10.486           ms/op
Client.listUser:listUser·p0.50        sample        25.395           ms/op
Client.listUser:listUser·p0.90        sample        34.669           ms/op
Client.listUser:listUser·p0.95        sample        36.477           ms/op
Client.listUser:listUser·p0.99        sample        43.445           ms/op
Client.listUser:listUser·p0.999       sample        44.485           ms/op
Client.listUser:listUser·p0.9999      sample        44.499           ms/op
Client.listUser:listUser·p1.00        sample        44.499           ms/op
