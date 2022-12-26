# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.655 ops/ms
Iteration   1: 1.184 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.184 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.599 ops/ms
Iteration   1: 3.349 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.349 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.286 ops/ms
Iteration   1: 2.448 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.448 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 0.616 ops/ms
Iteration   1: 0.921 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.921 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 23.924 ±(99.9%) 0.488 ms/op
Iteration   1: 15.266 ±(99.9%) 0.073 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  15.266 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 16.818 ±(99.9%) 0.363 ms/op
Iteration   1: 8.839 ±(99.9%) 0.071 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.839 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 22.598 ±(99.9%) 0.377 ms/op
Iteration   1: 8.755 ±(99.9%) 0.090 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.755 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 42.636 ±(99.9%) 2.638 ms/op
Iteration   1: 29.569 ±(99.9%) 0.366 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  29.569 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 25.394 ±(99.9%) 0.935 ms/op
Iteration   1: 15.000 ±(99.9%) 0.334 ms/op
                 createUser·p0.00:   5.644 ms/op
                 createUser·p0.50:   13.599 ms/op
                 createUser·p0.90:   20.906 ms/op
                 createUser·p0.95:   23.265 ms/op
                 createUser·p0.99:   35.122 ms/op
                 createUser·p0.999:  39.903 ms/op
                 createUser·p0.9999: 39.911 ms/op
                 createUser·p1.00:   39.911 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2123
  mean =     15.000 ±(99.9%) 0.334 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 39 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 525 
    [12.500, 15.000) = 856 
    [15.000, 17.500) = 296 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      5.644 ms/op
     p(50.0000) =     13.599 ms/op
     p(90.0000) =     20.906 ms/op
     p(95.0000) =     23.265 ms/op
     p(99.0000) =     35.122 ms/op
     p(99.9000) =     39.903 ms/op
     p(99.9900) =     39.911 ms/op
     p(99.9990) =     39.911 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.535 ±(99.9%) 0.439 ms/op
Iteration   1: 7.894 ±(99.9%) 0.165 ms/op
                 existUser·p0.00:   2.355 ms/op
                 existUser·p0.50:   7.889 ms/op
                 existUser·p0.90:   10.519 ms/op
                 existUser·p0.95:   12.485 ms/op
                 existUser·p0.99:   21.660 ms/op
                 existUser·p0.999:  30.704 ms/op
                 existUser·p0.9999: 31.130 ms/op
                 existUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4076
  mean =      7.894 ±(99.9%) 0.165 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 659 
    [ 5.000,  7.500) = 835 
    [ 7.500, 10.000) = 2104 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.355 ms/op
     p(50.0000) =      7.889 ms/op
     p(90.0000) =     10.519 ms/op
     p(95.0000) =     12.485 ms/op
     p(99.0000) =     21.660 ms/op
     p(99.9000) =     30.704 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     31.130 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 19.151 ±(99.9%) 0.665 ms/op
Iteration   1: 8.969 ±(99.9%) 0.187 ms/op
                 getUser·p0.00:   3.584 ms/op
                 getUser·p0.50:   8.012 ms/op
                 getUser·p0.90:   13.009 ms/op
                 getUser·p0.95:   15.836 ms/op
                 getUser·p0.99:   23.945 ms/op
                 getUser·p0.999:  25.953 ms/op
                 getUser·p0.9999: 32.145 ms/op
                 getUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3702
  mean =      8.969 ±(99.9%) 0.187 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 21 
    [ 5.000,  7.500) = 1468 
    [ 7.500, 10.000) = 1323 
    [10.000, 12.500) = 449 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.584 ms/op
     p(50.0000) =      8.012 ms/op
     p(90.0000) =     13.009 ms/op
     p(95.0000) =     15.836 ms/op
     p(99.0000) =     23.945 ms/op
     p(99.9000) =     25.953 ms/op
     p(99.9900) =     32.145 ms/op
     p(99.9990) =     32.145 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 36.837 ±(99.9%) 1.122 ms/op
Iteration   1: 26.603 ±(99.9%) 0.619 ms/op
                 listUser·p0.00:   9.667 ms/op
                 listUser·p0.50:   24.478 ms/op
                 listUser·p0.90:   35.979 ms/op
                 listUser·p0.95:   38.774 ms/op
                 listUser·p0.99:   48.294 ms/op
                 listUser·p0.999:  51.068 ms/op
                 listUser·p0.9999: 51.315 ms/op
                 listUser·p1.00:   51.315 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1208
  mean =     26.603 ±(99.9%) 0.619 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 1 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 115 
    [20.000, 25.000) = 506 
    [25.000, 30.000) = 286 
    [30.000, 35.000) = 160 
    [35.000, 40.000) = 97 
    [40.000, 45.000) = 17 
    [45.000, 50.000) = 24 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      9.667 ms/op
     p(50.0000) =     24.478 ms/op
     p(90.0000) =     35.979 ms/op
     p(95.0000) =     38.774 ms/op
     p(99.0000) =     48.294 ms/op
     p(99.9000) =     51.068 ms/op
     p(99.9900) =     51.315 ms/op
     p(99.9990) =     51.315 ms/op
     p(99.9999) =     51.315 ms/op
    p(100.0000) =     51.315 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.184          ops/ms
Client.existUser                       thrpt         3.349          ops/ms
Client.getUser                         thrpt         2.448          ops/ms
Client.listUser                        thrpt         0.921          ops/ms
Client.createUser                       avgt        15.266           ms/op
Client.existUser                        avgt         8.839           ms/op
Client.getUser                          avgt         8.755           ms/op
Client.listUser                         avgt        29.569           ms/op
Client.createUser                     sample  2123  15.000 ± 0.334   ms/op
Client.createUser:createUser·p0.00    sample         5.644           ms/op
Client.createUser:createUser·p0.50    sample        13.599           ms/op
Client.createUser:createUser·p0.90    sample        20.906           ms/op
Client.createUser:createUser·p0.95    sample        23.265           ms/op
Client.createUser:createUser·p0.99    sample        35.122           ms/op
Client.createUser:createUser·p0.999   sample        39.903           ms/op
Client.createUser:createUser·p0.9999  sample        39.911           ms/op
Client.createUser:createUser·p1.00    sample        39.911           ms/op
Client.existUser                      sample  4076   7.894 ± 0.165   ms/op
Client.existUser:existUser·p0.00      sample         2.355           ms/op
Client.existUser:existUser·p0.50      sample         7.889           ms/op
Client.existUser:existUser·p0.90      sample        10.519           ms/op
Client.existUser:existUser·p0.95      sample        12.485           ms/op
Client.existUser:existUser·p0.99      sample        21.660           ms/op
Client.existUser:existUser·p0.999     sample        30.704           ms/op
Client.existUser:existUser·p0.9999    sample        31.130           ms/op
Client.existUser:existUser·p1.00      sample        31.130           ms/op
Client.getUser                        sample  3702   8.969 ± 0.187   ms/op
Client.getUser:getUser·p0.00          sample         3.584           ms/op
Client.getUser:getUser·p0.50          sample         8.012           ms/op
Client.getUser:getUser·p0.90          sample        13.009           ms/op
Client.getUser:getUser·p0.95          sample        15.836           ms/op
Client.getUser:getUser·p0.99          sample        23.945           ms/op
Client.getUser:getUser·p0.999         sample        25.953           ms/op
Client.getUser:getUser·p0.9999        sample        32.145           ms/op
Client.getUser:getUser·p1.00          sample        32.145           ms/op
Client.listUser                       sample  1208  26.603 ± 0.619   ms/op
Client.listUser:listUser·p0.00        sample         9.667           ms/op
Client.listUser:listUser·p0.50        sample        24.478           ms/op
Client.listUser:listUser·p0.90        sample        35.979           ms/op
Client.listUser:listUser·p0.95        sample        38.774           ms/op
Client.listUser:listUser·p0.99        sample        48.294           ms/op
Client.listUser:listUser·p0.999       sample        51.068           ms/op
Client.listUser:listUser·p0.9999      sample        51.315           ms/op
Client.listUser:listUser·p1.00        sample        51.315           ms/op
