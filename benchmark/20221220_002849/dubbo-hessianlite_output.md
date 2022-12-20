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
# Warmup Iteration   1: 0.880 ops/ms
Iteration   1: 1.651 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.651 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 2.065 ops/ms
Iteration   1: 3.968 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.968 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.019 ops/ms
Iteration   1: 3.268 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.268 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 0.626 ops/ms
Iteration   1: 0.978 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.978 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 23.163 ±(99.9%) 0.425 ms/op
Iteration   1: 13.557 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  13.557 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:51
# Fork: 1 of 1
# Warmup Iteration   1: 13.629 ±(99.9%) 0.148 ms/op
Iteration   1: 5.095 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.095 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 19.438 ±(99.9%) 0.294 ms/op
Iteration   1: 7.529 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.529 ms/op


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
# Warmup Iteration   1: 32.846 ±(99.9%) 0.649 ms/op
Iteration   1: 21.073 ±(99.9%) 0.140 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  21.073 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 18.289 ±(99.9%) 0.797 ms/op
Iteration   1: 8.296 ±(99.9%) 0.170 ms/op
                 createUser·p0.00:   2.138 ms/op
                 createUser·p0.50:   7.102 ms/op
                 createUser·p0.90:   11.844 ms/op
                 createUser·p0.95:   16.220 ms/op
                 createUser·p0.99:   21.750 ms/op
                 createUser·p0.999:  24.833 ms/op
                 createUser·p0.9999: 26.051 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3840
  mean =      8.296 ±(99.9%) 0.170 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 36 
    [ 5.000,  7.500) = 2153 
    [ 7.500, 10.000) = 1084 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.138 ms/op
     p(50.0000) =      7.102 ms/op
     p(90.0000) =     11.844 ms/op
     p(95.0000) =     16.220 ms/op
     p(99.0000) =     21.750 ms/op
     p(99.9000) =     24.833 ms/op
     p(99.9900) =     26.051 ms/op
     p(99.9990) =     26.051 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 10.522 ±(99.9%) 0.304 ms/op
Iteration   1: 5.058 ±(99.9%) 0.095 ms/op
                 existUser·p0.00:   1.035 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   6.693 ms/op
                 existUser·p0.95:   9.077 ms/op
                 existUser·p0.99:   14.352 ms/op
                 existUser·p0.999:  21.594 ms/op
                 existUser·p0.9999: 21.660 ms/op
                 existUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6353
  mean =      5.058 ±(99.9%) 0.095 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 398 
    [ 2.500,  5.000) = 3280 
    [ 5.000,  7.500) = 2249 
    [ 7.500, 10.000) = 222 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      9.077 ms/op
     p(99.0000) =     14.352 ms/op
     p(99.9000) =     21.594 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 14.323 ±(99.9%) 0.448 ms/op
Iteration   1: 6.358 ±(99.9%) 0.127 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   6.070 ms/op
                 getUser·p0.90:   8.184 ms/op
                 getUser·p0.95:   9.945 ms/op
                 getUser·p0.99:   19.038 ms/op
                 getUser·p0.999:  30.768 ms/op
                 getUser·p0.9999: 45.744 ms/op
                 getUser·p1.00:   45.744 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5038
  mean =      6.358 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1146 
    [ 5.000, 10.000) = 3642 
    [10.000, 15.000) = 136 
    [15.000, 20.000) = 79 
    [20.000, 25.000) = 20 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 10 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      6.070 ms/op
     p(90.0000) =      8.184 ms/op
     p(95.0000) =      9.945 ms/op
     p(99.0000) =     19.038 ms/op
     p(99.9000) =     30.768 ms/op
     p(99.9900) =     45.744 ms/op
     p(99.9990) =     45.744 ms/op
     p(99.9999) =     45.744 ms/op
    p(100.0000) =     45.744 ms/op


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
# Warmup Iteration   1: 35.865 ±(99.9%) 1.487 ms/op
Iteration   1: 23.116 ±(99.9%) 0.509 ms/op
                 listUser·p0.00:   6.889 ms/op
                 listUser·p0.50:   22.741 ms/op
                 listUser·p0.90:   29.131 ms/op
                 listUser·p0.95:   35.612 ms/op
                 listUser·p0.99:   40.166 ms/op
                 listUser·p0.999:  56.036 ms/op
                 listUser·p0.9999: 57.606 ms/op
                 listUser·p1.00:   57.606 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1405
  mean =     23.116 ±(99.9%) 0.509 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 21 
    [10.000, 15.000) = 48 
    [15.000, 20.000) = 245 
    [20.000, 25.000) = 652 
    [25.000, 30.000) = 316 
    [30.000, 35.000) = 52 
    [35.000, 40.000) = 56 
    [40.000, 45.000) = 9 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      6.889 ms/op
     p(50.0000) =     22.741 ms/op
     p(90.0000) =     29.131 ms/op
     p(95.0000) =     35.612 ms/op
     p(99.0000) =     40.166 ms/op
     p(99.9000) =     56.036 ms/op
     p(99.9900) =     57.606 ms/op
     p(99.9990) =     57.606 ms/op
     p(99.9999) =     57.606 ms/op
    p(100.0000) =     57.606 ms/op


# Run complete. Total time: 00:01:29

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.651          ops/ms
Client.existUser                       thrpt         3.968          ops/ms
Client.getUser                         thrpt         3.268          ops/ms
Client.listUser                        thrpt         0.978          ops/ms
Client.createUser                       avgt        13.557           ms/op
Client.existUser                        avgt         5.095           ms/op
Client.getUser                          avgt         7.529           ms/op
Client.listUser                         avgt        21.073           ms/op
Client.createUser                     sample  3840   8.296 ± 0.170   ms/op
Client.createUser:createUser·p0.00    sample         2.138           ms/op
Client.createUser:createUser·p0.50    sample         7.102           ms/op
Client.createUser:createUser·p0.90    sample        11.844           ms/op
Client.createUser:createUser·p0.95    sample        16.220           ms/op
Client.createUser:createUser·p0.99    sample        21.750           ms/op
Client.createUser:createUser·p0.999   sample        24.833           ms/op
Client.createUser:createUser·p0.9999  sample        26.051           ms/op
Client.createUser:createUser·p1.00    sample        26.051           ms/op
Client.existUser                      sample  6353   5.058 ± 0.095   ms/op
Client.existUser:existUser·p0.00      sample         1.035           ms/op
Client.existUser:existUser·p0.50      sample         4.719           ms/op
Client.existUser:existUser·p0.90      sample         6.693           ms/op
Client.existUser:existUser·p0.95      sample         9.077           ms/op
Client.existUser:existUser·p0.99      sample        14.352           ms/op
Client.existUser:existUser·p0.999     sample        21.594           ms/op
Client.existUser:existUser·p0.9999    sample        21.660           ms/op
Client.existUser:existUser·p1.00      sample        21.660           ms/op
Client.getUser                        sample  5038   6.358 ± 0.127   ms/op
Client.getUser:getUser·p0.00          sample         1.065           ms/op
Client.getUser:getUser·p0.50          sample         6.070           ms/op
Client.getUser:getUser·p0.90          sample         8.184           ms/op
Client.getUser:getUser·p0.95          sample         9.945           ms/op
Client.getUser:getUser·p0.99          sample        19.038           ms/op
Client.getUser:getUser·p0.999         sample        30.768           ms/op
Client.getUser:getUser·p0.9999        sample        45.744           ms/op
Client.getUser:getUser·p1.00          sample        45.744           ms/op
Client.listUser                       sample  1405  23.116 ± 0.509   ms/op
Client.listUser:listUser·p0.00        sample         6.889           ms/op
Client.listUser:listUser·p0.50        sample        22.741           ms/op
Client.listUser:listUser·p0.90        sample        29.131           ms/op
Client.listUser:listUser·p0.95        sample        35.612           ms/op
Client.listUser:listUser·p0.99        sample        40.166           ms/op
Client.listUser:listUser·p0.999       sample        56.036           ms/op
Client.listUser:listUser·p0.9999      sample        57.606           ms/op
Client.listUser:listUser·p1.00        sample        57.606           ms/op
