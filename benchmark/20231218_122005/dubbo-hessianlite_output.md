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
# Warmup Iteration   1: 2.452 ops/ms
Iteration   1: 6.194 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.194 ops/ms


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
# Warmup Iteration   1: 6.536 ops/ms
Iteration   1: 13.107 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.107 ops/ms


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
# Warmup Iteration   1: 4.439 ops/ms
Iteration   1: 8.576 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.576 ops/ms


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
# Warmup Iteration   1: 1.905 ops/ms
Iteration   1: 3.266 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.266 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.574 ±(99.9%) 0.078 ms/op
Iteration   1: 3.181 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.181 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.207 ±(99.9%) 0.076 ms/op
Iteration   1: 1.928 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.928 ms/op


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
# Warmup Iteration   1: 4.799 ±(99.9%) 0.051 ms/op
Iteration   1: 3.268 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.268 ms/op


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
# Warmup Iteration   1: 12.925 ±(99.9%) 0.287 ms/op
Iteration   1: 8.632 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.632 ms/op


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
# Warmup Iteration   1: 4.991 ±(99.9%) 0.110 ms/op
Iteration   1: 3.184 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.769 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   9.306 ms/op
                 createUser·p0.999:  23.593 ms/op
                 createUser·p0.9999: 23.626 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10097
  mean =      3.184 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1907 
    [ 2.500,  5.000) = 7841 
    [ 5.000,  7.500) = 142 
    [ 7.500, 10.000) = 116 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.769 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     23.593 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 2.813 ±(99.9%) 0.057 ms/op
Iteration   1: 1.773 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   1.655 ms/op
                 existUser·p0.90:   2.025 ms/op
                 existUser·p0.95:   2.208 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  18.973 ms/op
                 existUser·p0.9999: 19.071 ms/op
                 existUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18151
  mean =      1.773 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 208 
    [ 1.250,  2.500) = 17521 
    [ 2.500,  3.750) = 309 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      1.655 ms/op
     p(90.0000) =      2.025 ms/op
     p(95.0000) =      2.208 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 4.696 ±(99.9%) 0.165 ms/op
Iteration   1: 3.506 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.165 ms/op
                 getUser·p0.999:  7.577 ms/op
                 getUser·p0.9999: 7.774 ms/op
                 getUser·p1.00:   7.774 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9353
  mean =      3.506 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 12 
    [1.500, 2.000) = 44 
    [2.000, 2.500) = 457 
    [2.500, 3.000) = 1602 
    [3.000, 3.500) = 2983 
    [3.500, 4.000) = 2389 
    [4.000, 4.500) = 1236 
    [4.500, 5.000) = 313 
    [5.000, 5.500) = 115 
    [5.500, 6.000) = 93 
    [6.000, 6.500) = 34 
    [6.500, 7.000) = 51 
    [7.000, 7.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.165 ms/op
     p(99.9000) =      7.577 ms/op
     p(99.9900) =      7.774 ms/op
     p(99.9990) =      7.774 ms/op
     p(99.9999) =      7.774 ms/op
    p(100.0000) =      7.774 ms/op


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
# Warmup Iteration   1: 12.798 ±(99.9%) 0.438 ms/op
Iteration   1: 8.035 ±(99.9%) 0.127 ms/op
                 listUser·p0.00:   2.929 ms/op
                 listUser·p0.50:   7.668 ms/op
                 listUser·p0.90:   10.248 ms/op
                 listUser·p0.95:   11.280 ms/op
                 listUser·p0.99:   14.483 ms/op
                 listUser·p0.999:  30.487 ms/op
                 listUser·p0.9999: 33.948 ms/op
                 listUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3984
  mean =      8.035 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 87 
    [ 5.000,  7.500) = 1703 
    [ 7.500, 10.000) = 1736 
    [10.000, 12.500) = 353 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.929 ms/op
     p(50.0000) =      7.668 ms/op
     p(90.0000) =     10.248 ms/op
     p(95.0000) =     11.280 ms/op
     p(99.0000) =     14.483 ms/op
     p(99.9000) =     30.487 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.194          ops/ms
Client.existUser                       thrpt         13.107          ops/ms
Client.getUser                         thrpt          8.576          ops/ms
Client.listUser                        thrpt          3.266          ops/ms
Client.createUser                       avgt          3.181           ms/op
Client.existUser                        avgt          1.928           ms/op
Client.getUser                          avgt          3.268           ms/op
Client.listUser                         avgt          8.632           ms/op
Client.createUser                     sample  10097   3.184 ± 0.052   ms/op
Client.createUser:createUser·p0.00    sample          0.764           ms/op
Client.createUser:createUser·p0.50    sample          2.986           ms/op
Client.createUser:createUser·p0.90    sample          3.769           ms/op
Client.createUser:createUser·p0.95    sample          4.243           ms/op
Client.createUser:createUser·p0.99    sample          9.306           ms/op
Client.createUser:createUser·p0.999   sample         23.593           ms/op
Client.createUser:createUser·p0.9999  sample         23.626           ms/op
Client.createUser:createUser·p1.00    sample         23.626           ms/op
Client.existUser                      sample  18151   1.773 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.665           ms/op
Client.existUser:existUser·p0.50      sample          1.655           ms/op
Client.existUser:existUser·p0.90      sample          2.025           ms/op
Client.existUser:existUser·p0.95      sample          2.208           ms/op
Client.existUser:existUser·p0.99      sample          3.465           ms/op
Client.existUser:existUser·p0.999     sample         18.973           ms/op
Client.existUser:existUser·p0.9999    sample         19.071           ms/op
Client.existUser:existUser·p1.00      sample         19.071           ms/op
Client.getUser                        sample   9353   3.506 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          1.106           ms/op
Client.getUser:getUser·p0.50          sample          3.432           ms/op
Client.getUser:getUser·p0.90          sample          4.342           ms/op
Client.getUser:getUser·p0.95          sample          4.628           ms/op
Client.getUser:getUser·p0.99          sample          6.165           ms/op
Client.getUser:getUser·p0.999         sample          7.577           ms/op
Client.getUser:getUser·p0.9999        sample          7.774           ms/op
Client.getUser:getUser·p1.00          sample          7.774           ms/op
Client.listUser                       sample   3984   8.035 ± 0.127   ms/op
Client.listUser:listUser·p0.00        sample          2.929           ms/op
Client.listUser:listUser·p0.50        sample          7.668           ms/op
Client.listUser:listUser·p0.90        sample         10.248           ms/op
Client.listUser:listUser·p0.95        sample         11.280           ms/op
Client.listUser:listUser·p0.99        sample         14.483           ms/op
Client.listUser:listUser·p0.999       sample         30.487           ms/op
Client.listUser:listUser·p0.9999      sample         33.948           ms/op
Client.listUser:listUser·p1.00        sample         33.948           ms/op
