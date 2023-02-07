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
# Warmup Iteration   1: 0.562 ops/ms
Iteration   1: 1.001 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.001 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:28
# Fork: 1 of 1
# Warmup Iteration   1: 1.520 ops/ms
Iteration   1: 3.868 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.868 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 1.091 ops/ms
Iteration   1: 2.544 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.544 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 0.605 ops/ms
Iteration   1: 0.775 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.775 ops/ms


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
# Warmup Iteration   1: 37.624 ±(99.9%) 0.586 ms/op
Iteration   1: 16.451 ±(99.9%) 0.269 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.451 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 16.910 ±(99.9%) 0.265 ms/op
Iteration   1: 10.147 ±(99.9%) 0.200 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.147 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 27.660 ±(99.9%) 0.496 ms/op
Iteration   1: 12.433 ±(99.9%) 0.084 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  12.433 ms/op


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
# Warmup Iteration   1: 41.990 ±(99.9%) 0.795 ms/op
Iteration   1: 26.818 ±(99.9%) 0.245 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  26.818 ms/op


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
# Warmup Iteration   1: 24.742 ±(99.9%) 1.317 ms/op
Iteration   1: 12.387 ±(99.9%) 0.403 ms/op
                 createUser·p0.00:   3.547 ms/op
                 createUser·p0.50:   11.452 ms/op
                 createUser·p0.90:   20.437 ms/op
                 createUser·p0.95:   28.901 ms/op
                 createUser·p0.99:   35.466 ms/op
                 createUser·p0.999:  41.293 ms/op
                 createUser·p0.9999: 48.300 ms/op
                 createUser·p1.00:   48.300 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2582
  mean =     12.387 ±(99.9%) 0.403 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8 
    [ 5.000, 10.000) = 1067 
    [10.000, 15.000) = 1060 
    [15.000, 20.000) = 183 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 123 
    [30.000, 35.000) = 49 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      3.547 ms/op
     p(50.0000) =     11.452 ms/op
     p(90.0000) =     20.437 ms/op
     p(95.0000) =     28.901 ms/op
     p(99.0000) =     35.466 ms/op
     p(99.9000) =     41.293 ms/op
     p(99.9900) =     48.300 ms/op
     p(99.9990) =     48.300 ms/op
     p(99.9999) =     48.300 ms/op
    p(100.0000) =     48.300 ms/op


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
# Warmup Iteration   1: 14.084 ±(99.9%) 0.531 ms/op
Iteration   1: 6.785 ±(99.9%) 0.156 ms/op
                 existUser·p0.00:   1.995 ms/op
                 existUser·p0.50:   6.480 ms/op
                 existUser·p0.90:   10.284 ms/op
                 existUser·p0.95:   11.583 ms/op
                 existUser·p0.99:   19.497 ms/op
                 existUser·p0.999:  25.503 ms/op
                 existUser·p0.9999: 25.592 ms/op
                 existUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4702
  mean =      6.785 ±(99.9%) 0.156 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 1608 
    [ 5.000,  7.500) = 1624 
    [ 7.500, 10.000) = 909 
    [10.000, 12.500) = 395 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.995 ms/op
     p(50.0000) =      6.480 ms/op
     p(90.0000) =     10.284 ms/op
     p(95.0000) =     11.583 ms/op
     p(99.0000) =     19.497 ms/op
     p(99.9000) =     25.503 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     25.592 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 20.614 ±(99.9%) 0.654 ms/op
Iteration   1: 8.787 ±(99.9%) 0.224 ms/op
                 getUser·p0.00:   3.105 ms/op
                 getUser·p0.50:   7.520 ms/op
                 getUser·p0.90:   12.757 ms/op
                 getUser·p0.95:   18.514 ms/op
                 getUser·p0.99:   26.633 ms/op
                 getUser·p0.999:  28.639 ms/op
                 getUser·p0.9999: 29.262 ms/op
                 getUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3621
  mean =      8.787 ±(99.9%) 0.224 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 47 
    [ 5.000,  7.500) = 1758 
    [ 7.500, 10.000) = 1023 
    [10.000, 12.500) = 412 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      3.105 ms/op
     p(50.0000) =      7.520 ms/op
     p(90.0000) =     12.757 ms/op
     p(95.0000) =     18.514 ms/op
     p(99.0000) =     26.633 ms/op
     p(99.9000) =     28.639 ms/op
     p(99.9900) =     29.262 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 46.952 ±(99.9%) 2.975 ms/op
Iteration   1: 29.304 ±(99.9%) 0.797 ms/op
                 listUser·p0.00:   13.992 ms/op
                 listUser·p0.50:   28.082 ms/op
                 listUser·p0.90:   37.100 ms/op
                 listUser·p0.95:   38.905 ms/op
                 listUser·p0.99:   67.836 ms/op
                 listUser·p0.999:  73.999 ms/op
                 listUser·p0.9999: 74.056 ms/op
                 listUser·p1.00:   74.056 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1108
  mean =     29.304 ±(99.9%) 0.797 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 1 
    [15.000, 20.000) = 66 
    [20.000, 25.000) = 257 
    [25.000, 30.000) = 356 
    [30.000, 35.000) = 204 
    [35.000, 40.000) = 180 
    [40.000, 45.000) = 12 
    [45.000, 50.000) = 7 
    [50.000, 55.000) = 5 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 2 
    [65.000, 70.000) = 8 
    [70.000, 75.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =     13.992 ms/op
     p(50.0000) =     28.082 ms/op
     p(90.0000) =     37.100 ms/op
     p(95.0000) =     38.905 ms/op
     p(99.0000) =     67.836 ms/op
     p(99.9000) =     73.999 ms/op
     p(99.9900) =     74.056 ms/op
     p(99.9990) =     74.056 ms/op
     p(99.9999) =     74.056 ms/op
    p(100.0000) =     74.056 ms/op


# Run complete. Total time: 00:01:35

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.001          ops/ms
Client.existUser                       thrpt         3.868          ops/ms
Client.getUser                         thrpt         2.544          ops/ms
Client.listUser                        thrpt         0.775          ops/ms
Client.createUser                       avgt        16.451           ms/op
Client.existUser                        avgt        10.147           ms/op
Client.getUser                          avgt        12.433           ms/op
Client.listUser                         avgt        26.818           ms/op
Client.createUser                     sample  2582  12.387 ± 0.403   ms/op
Client.createUser:createUser·p0.00    sample         3.547           ms/op
Client.createUser:createUser·p0.50    sample        11.452           ms/op
Client.createUser:createUser·p0.90    sample        20.437           ms/op
Client.createUser:createUser·p0.95    sample        28.901           ms/op
Client.createUser:createUser·p0.99    sample        35.466           ms/op
Client.createUser:createUser·p0.999   sample        41.293           ms/op
Client.createUser:createUser·p0.9999  sample        48.300           ms/op
Client.createUser:createUser·p1.00    sample        48.300           ms/op
Client.existUser                      sample  4702   6.785 ± 0.156   ms/op
Client.existUser:existUser·p0.00      sample         1.995           ms/op
Client.existUser:existUser·p0.50      sample         6.480           ms/op
Client.existUser:existUser·p0.90      sample        10.284           ms/op
Client.existUser:existUser·p0.95      sample        11.583           ms/op
Client.existUser:existUser·p0.99      sample        19.497           ms/op
Client.existUser:existUser·p0.999     sample        25.503           ms/op
Client.existUser:existUser·p0.9999    sample        25.592           ms/op
Client.existUser:existUser·p1.00      sample        25.592           ms/op
Client.getUser                        sample  3621   8.787 ± 0.224   ms/op
Client.getUser:getUser·p0.00          sample         3.105           ms/op
Client.getUser:getUser·p0.50          sample         7.520           ms/op
Client.getUser:getUser·p0.90          sample        12.757           ms/op
Client.getUser:getUser·p0.95          sample        18.514           ms/op
Client.getUser:getUser·p0.99          sample        26.633           ms/op
Client.getUser:getUser·p0.999         sample        28.639           ms/op
Client.getUser:getUser·p0.9999        sample        29.262           ms/op
Client.getUser:getUser·p1.00          sample        29.262           ms/op
Client.listUser                       sample  1108  29.304 ± 0.797   ms/op
Client.listUser:listUser·p0.00        sample        13.992           ms/op
Client.listUser:listUser·p0.50        sample        28.082           ms/op
Client.listUser:listUser·p0.90        sample        37.100           ms/op
Client.listUser:listUser·p0.95        sample        38.905           ms/op
Client.listUser:listUser·p0.99        sample        67.836           ms/op
Client.listUser:listUser·p0.999       sample        73.999           ms/op
Client.listUser:listUser·p0.9999      sample        74.056           ms/op
Client.listUser:listUser·p1.00        sample        74.056           ms/op
