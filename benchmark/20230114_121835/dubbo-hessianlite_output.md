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
# Warmup Iteration   1: 0.771 ops/ms
Iteration   1: 2.152 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.152 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 3.139 ops/ms
Iteration   1: 6.403 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.403 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.871 ops/ms
Iteration   1: 4.545 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.545 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 0.840 ops/ms
Iteration   1: 1.343 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.343 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 17.611 ±(99.9%) 0.287 ms/op
Iteration   1: 7.287 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.287 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.148 ±(99.9%) 0.112 ms/op
Iteration   1: 4.166 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.166 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.302 ±(99.9%) 0.149 ms/op
Iteration   1: 5.114 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.114 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 26.269 ±(99.9%) 0.442 ms/op
Iteration   1: 17.960 ±(99.9%) 0.059 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.960 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.172 ±(99.9%) 0.460 ms/op
Iteration   1: 8.115 ±(99.9%) 0.161 ms/op
                 createUser·p0.00:   1.810 ms/op
                 createUser·p0.50:   8.167 ms/op
                 createUser·p0.90:   9.159 ms/op
                 createUser·p0.95:   13.615 ms/op
                 createUser·p0.99:   17.473 ms/op
                 createUser·p0.999:  28.228 ms/op
                 createUser·p0.9999: 28.869 ms/op
                 createUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3976
  mean =      8.115 ±(99.9%) 0.161 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188 
    [ 2.500,  5.000) = 321 
    [ 5.000,  7.500) = 123 
    [ 7.500, 10.000) = 3030 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.810 ms/op
     p(50.0000) =      8.167 ms/op
     p(90.0000) =      9.159 ms/op
     p(95.0000) =     13.615 ms/op
     p(99.0000) =     17.473 ms/op
     p(99.9000) =     28.228 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.117 ±(99.9%) 0.211 ms/op
Iteration   1: 4.517 ±(99.9%) 0.078 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   9.657 ms/op
                 existUser·p0.99:   13.894 ms/op
                 existUser·p0.999:  16.663 ms/op
                 existUser·p0.9999: 19.005 ms/op
                 existUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7088
  mean =      4.517 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 94 
    [ 2.500,  3.750) = 1586 
    [ 3.750,  5.000) = 4715 
    [ 5.000,  6.250) = 127 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      4.051 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      9.657 ms/op
     p(99.0000) =     13.894 ms/op
     p(99.9000) =     16.663 ms/op
     p(99.9900) =     19.005 ms/op
     p(99.9990) =     19.005 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 9.315 ±(99.9%) 0.363 ms/op
Iteration   1: 4.880 ±(99.9%) 0.073 ms/op
                 getUser·p0.00:   1.518 ms/op
                 getUser·p0.50:   4.604 ms/op
                 getUser·p0.90:   5.898 ms/op
                 getUser·p0.95:   7.208 ms/op
                 getUser·p0.99:   15.931 ms/op
                 getUser·p0.999:  19.169 ms/op
                 getUser·p0.9999: 19.923 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6621
  mean =      4.880 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 77 
    [ 2.500,  3.750) = 796 
    [ 3.750,  5.000) = 3898 
    [ 5.000,  6.250) = 1356 
    [ 6.250,  7.500) = 227 
    [ 7.500,  8.750) = 99 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.898 ms/op
     p(95.0000) =      7.208 ms/op
     p(99.0000) =     15.931 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 27.378 ±(99.9%) 0.796 ms/op
Iteration   1: 16.849 ±(99.9%) 0.265 ms/op
                 listUser·p0.00:   4.202 ms/op
                 listUser·p0.50:   16.876 ms/op
                 listUser·p0.90:   20.775 ms/op
                 listUser·p0.95:   24.248 ms/op
                 listUser·p0.99:   28.083 ms/op
                 listUser·p0.999:  31.795 ms/op
                 listUser·p0.9999: 31.883 ms/op
                 listUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1896
  mean =     16.849 ±(99.9%) 0.265 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 2 
    [ 5.000,  7.500) = 8 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 376 
    [15.000, 17.500) = 817 
    [17.500, 20.000) = 338 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      4.202 ms/op
     p(50.0000) =     16.876 ms/op
     p(90.0000) =     20.775 ms/op
     p(95.0000) =     24.248 ms/op
     p(99.0000) =     28.083 ms/op
     p(99.9000) =     31.795 ms/op
     p(99.9900) =     31.883 ms/op
     p(99.9990) =     31.883 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.152          ops/ms
Client.existUser                       thrpt         6.403          ops/ms
Client.getUser                         thrpt         4.545          ops/ms
Client.listUser                        thrpt         1.343          ops/ms
Client.createUser                       avgt         7.287           ms/op
Client.existUser                        avgt         4.166           ms/op
Client.getUser                          avgt         5.114           ms/op
Client.listUser                         avgt        17.960           ms/op
Client.createUser                     sample  3976   8.115 ± 0.161   ms/op
Client.createUser:createUser·p0.00    sample         1.810           ms/op
Client.createUser:createUser·p0.50    sample         8.167           ms/op
Client.createUser:createUser·p0.90    sample         9.159           ms/op
Client.createUser:createUser·p0.95    sample        13.615           ms/op
Client.createUser:createUser·p0.99    sample        17.473           ms/op
Client.createUser:createUser·p0.999   sample        28.228           ms/op
Client.createUser:createUser·p0.9999  sample        28.869           ms/op
Client.createUser:createUser·p1.00    sample        28.869           ms/op
Client.existUser                      sample  7088   4.517 ± 0.078   ms/op
Client.existUser:existUser·p0.00      sample         1.110           ms/op
Client.existUser:existUser·p0.50      sample         4.051           ms/op
Client.existUser:existUser·p0.90      sample         4.874           ms/op
Client.existUser:existUser·p0.95      sample         9.657           ms/op
Client.existUser:existUser·p0.99      sample        13.894           ms/op
Client.existUser:existUser·p0.999     sample        16.663           ms/op
Client.existUser:existUser·p0.9999    sample        19.005           ms/op
Client.existUser:existUser·p1.00      sample        19.005           ms/op
Client.getUser                        sample  6621   4.880 ± 0.073   ms/op
Client.getUser:getUser·p0.00          sample         1.518           ms/op
Client.getUser:getUser·p0.50          sample         4.604           ms/op
Client.getUser:getUser·p0.90          sample         5.898           ms/op
Client.getUser:getUser·p0.95          sample         7.208           ms/op
Client.getUser:getUser·p0.99          sample        15.931           ms/op
Client.getUser:getUser·p0.999         sample        19.169           ms/op
Client.getUser:getUser·p0.9999        sample        19.923           ms/op
Client.getUser:getUser·p1.00          sample        19.923           ms/op
Client.listUser                       sample  1896  16.849 ± 0.265   ms/op
Client.listUser:listUser·p0.00        sample         4.202           ms/op
Client.listUser:listUser·p0.50        sample        16.876           ms/op
Client.listUser:listUser·p0.90        sample        20.775           ms/op
Client.listUser:listUser·p0.95        sample        24.248           ms/op
Client.listUser:listUser·p0.99        sample        28.083           ms/op
Client.listUser:listUser·p0.999       sample        31.795           ms/op
Client.listUser:listUser·p0.9999      sample        31.883           ms/op
Client.listUser:listUser·p1.00        sample        31.883           ms/op
