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
# Warmup Iteration   1: 0.365 ops/ms
Iteration   1: 0.930 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  0.930 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:27
# Fork: 1 of 1
# Warmup Iteration   1: 1.450 ops/ms
Iteration   1: 2.764 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.764 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 0.983 ops/ms
Iteration   1: 1.928 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  1.928 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 0.548 ops/ms
Iteration   1: 0.743 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.743 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 31.712 ±(99.9%) 0.621 ms/op
Iteration   1: 17.013 ±(99.9%) 0.186 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  17.013 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 20.657 ±(99.9%) 0.425 ms/op
Iteration   1: 12.266 ±(99.9%) 0.096 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.266 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 25.185 ±(99.9%) 0.540 ms/op
Iteration   1: 14.447 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  14.447 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 45.261 ±(99.9%) 0.898 ms/op
Iteration   1: 27.064 ±(99.9%) 0.284 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  27.064 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 26.053 ±(99.9%) 1.091 ms/op
Iteration   1: 11.913 ±(99.9%) 0.404 ms/op
                 createUser·p0.00:   3.600 ms/op
                 createUser·p0.50:   10.158 ms/op
                 createUser·p0.90:   20.513 ms/op
                 createUser·p0.95:   28.000 ms/op
                 createUser·p0.99:   37.064 ms/op
                 createUser·p0.999:  38.394 ms/op
                 createUser·p0.9999: 38.928 ms/op
                 createUser·p1.00:   38.928 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2644
  mean =     11.913 ±(99.9%) 0.404 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 10 
    [ 5.000,  7.500) = 648 
    [ 7.500, 10.000) = 626 
    [10.000, 12.500) = 587 
    [12.500, 15.000) = 316 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 50 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      3.600 ms/op
     p(50.0000) =     10.158 ms/op
     p(90.0000) =     20.513 ms/op
     p(95.0000) =     28.000 ms/op
     p(99.0000) =     37.064 ms/op
     p(99.9000) =     38.394 ms/op
     p(99.9900) =     38.928 ms/op
     p(99.9990) =     38.928 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 17.036 ±(99.9%) 0.628 ms/op
Iteration   1: 7.994 ±(99.9%) 0.174 ms/op
                 existUser·p0.00:   1.976 ms/op
                 existUser·p0.50:   7.741 ms/op
                 existUser·p0.90:   11.125 ms/op
                 existUser·p0.95:   12.442 ms/op
                 existUser·p0.99:   22.348 ms/op
                 existUser·p0.999:  27.265 ms/op
                 existUser·p0.9999: 28.901 ms/op
                 existUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 3991
  mean =      7.994 ±(99.9%) 0.174 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52 
    [ 2.500,  5.000) = 576 
    [ 5.000,  7.500) = 1180 
    [ 7.500, 10.000) = 1496 
    [10.000, 12.500) = 488 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.976 ms/op
     p(50.0000) =      7.741 ms/op
     p(90.0000) =     11.125 ms/op
     p(95.0000) =     12.442 ms/op
     p(99.0000) =     22.348 ms/op
     p(99.9000) =     27.265 ms/op
     p(99.9900) =     28.901 ms/op
     p(99.9990) =     28.901 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 21.873 ±(99.9%) 0.917 ms/op
Iteration   1: 8.858 ±(99.9%) 0.275 ms/op
                 getUser·p0.00:   2.081 ms/op
                 getUser·p0.50:   7.447 ms/op
                 getUser·p0.90:   14.639 ms/op
                 getUser·p0.95:   18.745 ms/op
                 getUser·p0.99:   29.655 ms/op
                 getUser·p0.999:  43.672 ms/op
                 getUser·p0.9999: 44.040 ms/op
                 getUser·p1.00:   44.040 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3618
  mean =      8.858 ±(99.9%) 0.275 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 245 
    [ 5.000, 10.000) = 2619 
    [10.000, 15.000) = 398 
    [15.000, 20.000) = 229 
    [20.000, 25.000) = 73 
    [25.000, 30.000) = 21 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      2.081 ms/op
     p(50.0000) =      7.447 ms/op
     p(90.0000) =     14.639 ms/op
     p(95.0000) =     18.745 ms/op
     p(99.0000) =     29.655 ms/op
     p(99.9000) =     43.672 ms/op
     p(99.9900) =     44.040 ms/op
     p(99.9990) =     44.040 ms/op
     p(99.9999) =     44.040 ms/op
    p(100.0000) =     44.040 ms/op


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
# Warmup Iteration   1: 48.966 ±(99.9%) 2.020 ms/op
Iteration   1: 29.376 ±(99.9%) 0.695 ms/op
                 listUser·p0.00:   13.287 ms/op
                 listUser·p0.50:   29.573 ms/op
                 listUser·p0.90:   36.104 ms/op
                 listUser·p0.95:   40.370 ms/op
                 listUser·p0.99:   53.215 ms/op
                 listUser·p0.999:  58.923 ms/op
                 listUser·p0.9999: 59.048 ms/op
                 listUser·p1.00:   59.048 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1090
  mean =     29.376 ±(99.9%) 0.695 ms/op

  Histogram, ms/op:
    [10.000, 15.000) = 13 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 337 
    [25.000, 30.000) = 226 
    [30.000, 35.000) = 374 
    [35.000, 40.000) = 80 
    [40.000, 45.000) = 9 
    [45.000, 50.000) = 11 
    [50.000, 55.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =     13.287 ms/op
     p(50.0000) =     29.573 ms/op
     p(90.0000) =     36.104 ms/op
     p(95.0000) =     40.370 ms/op
     p(99.0000) =     53.215 ms/op
     p(99.9000) =     58.923 ms/op
     p(99.9900) =     59.048 ms/op
     p(99.9990) =     59.048 ms/op
     p(99.9999) =     59.048 ms/op
    p(100.0000) =     59.048 ms/op


# Run complete. Total time: 00:01:35

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         0.930          ops/ms
Client.existUser                       thrpt         2.764          ops/ms
Client.getUser                         thrpt         1.928          ops/ms
Client.listUser                        thrpt         0.743          ops/ms
Client.createUser                       avgt        17.013           ms/op
Client.existUser                        avgt        12.266           ms/op
Client.getUser                          avgt        14.447           ms/op
Client.listUser                         avgt        27.064           ms/op
Client.createUser                     sample  2644  11.913 ± 0.404   ms/op
Client.createUser:createUser·p0.00    sample         3.600           ms/op
Client.createUser:createUser·p0.50    sample        10.158           ms/op
Client.createUser:createUser·p0.90    sample        20.513           ms/op
Client.createUser:createUser·p0.95    sample        28.000           ms/op
Client.createUser:createUser·p0.99    sample        37.064           ms/op
Client.createUser:createUser·p0.999   sample        38.394           ms/op
Client.createUser:createUser·p0.9999  sample        38.928           ms/op
Client.createUser:createUser·p1.00    sample        38.928           ms/op
Client.existUser                      sample  3991   7.994 ± 0.174   ms/op
Client.existUser:existUser·p0.00      sample         1.976           ms/op
Client.existUser:existUser·p0.50      sample         7.741           ms/op
Client.existUser:existUser·p0.90      sample        11.125           ms/op
Client.existUser:existUser·p0.95      sample        12.442           ms/op
Client.existUser:existUser·p0.99      sample        22.348           ms/op
Client.existUser:existUser·p0.999     sample        27.265           ms/op
Client.existUser:existUser·p0.9999    sample        28.901           ms/op
Client.existUser:existUser·p1.00      sample        28.901           ms/op
Client.getUser                        sample  3618   8.858 ± 0.275   ms/op
Client.getUser:getUser·p0.00          sample         2.081           ms/op
Client.getUser:getUser·p0.50          sample         7.447           ms/op
Client.getUser:getUser·p0.90          sample        14.639           ms/op
Client.getUser:getUser·p0.95          sample        18.745           ms/op
Client.getUser:getUser·p0.99          sample        29.655           ms/op
Client.getUser:getUser·p0.999         sample        43.672           ms/op
Client.getUser:getUser·p0.9999        sample        44.040           ms/op
Client.getUser:getUser·p1.00          sample        44.040           ms/op
Client.listUser                       sample  1090  29.376 ± 0.695   ms/op
Client.listUser:listUser·p0.00        sample        13.287           ms/op
Client.listUser:listUser·p0.50        sample        29.573           ms/op
Client.listUser:listUser·p0.90        sample        36.104           ms/op
Client.listUser:listUser·p0.95        sample        40.370           ms/op
Client.listUser:listUser·p0.99        sample        53.215           ms/op
Client.listUser:listUser·p0.999       sample        58.923           ms/op
Client.listUser:listUser·p0.9999      sample        59.048           ms/op
Client.listUser:listUser·p1.00        sample        59.048           ms/op
