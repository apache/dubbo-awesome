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
# Warmup Iteration   1: 1.003 ops/ms
Iteration   1: 2.936 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.936 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:26
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ops/ms
Iteration   1: 6.998 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.998 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 2.258 ops/ms
Iteration   1: 4.924 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.924 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 0.867 ops/ms
Iteration   1: 1.277 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.277 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 12.183 ±(99.9%) 0.300 ms/op
Iteration   1: 6.224 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.224 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 9.101 ±(99.9%) 0.205 ms/op
Iteration   1: 3.864 ±(99.9%) 0.061 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.864 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.983 ±(99.9%) 0.254 ms/op
Iteration   1: 6.864 ±(99.9%) 0.075 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.864 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 28.049 ±(99.9%) 0.797 ms/op
Iteration   1: 23.305 ±(99.9%) 0.379 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  23.305 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 10.235 ±(99.9%) 0.279 ms/op
Iteration   1: 4.781 ±(99.9%) 0.172 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.774 ms/op
                 createUser·p0.90:   6.341 ms/op
                 createUser·p0.95:   7.752 ms/op
                 createUser·p0.99:   15.843 ms/op
                 createUser·p0.999:  53.608 ms/op
                 createUser·p0.9999: 55.378 ms/op
                 createUser·p1.00:   55.378 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6674
  mean =      4.781 ±(99.9%) 0.172 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4834 
    [ 5.000, 10.000) = 1586 
    [10.000, 15.000) = 162 
    [15.000, 20.000) = 28 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 30 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.774 ms/op
     p(90.0000) =      6.341 ms/op
     p(95.0000) =      7.752 ms/op
     p(99.0000) =     15.843 ms/op
     p(99.9000) =     53.608 ms/op
     p(99.9900) =     55.378 ms/op
     p(99.9990) =     55.378 ms/op
     p(99.9999) =     55.378 ms/op
    p(100.0000) =     55.378 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.311 ±(99.9%) 0.244 ms/op
Iteration   1: 2.929 ±(99.9%) 0.064 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   2.265 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   7.709 ms/op
                 existUser·p0.99:   12.314 ms/op
                 existUser·p0.999:  17.302 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 11239
  mean =      2.929 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 6527 
    [ 2.500,  3.750) = 3233 
    [ 3.750,  5.000) = 451 
    [ 5.000,  6.250) = 236 
    [ 6.250,  7.500) = 135 
    [ 7.500,  8.750) = 144 
    [ 8.750, 10.000) = 158 
    [10.000, 11.250) = 152 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      2.265 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      7.709 ms/op
     p(99.0000) =     12.314 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 10.793 ±(99.9%) 0.301 ms/op
Iteration   1: 6.059 ±(99.9%) 0.099 ms/op
                 getUser·p0.00:   1.819 ms/op
                 getUser·p0.50:   5.571 ms/op
                 getUser·p0.90:   9.044 ms/op
                 getUser·p0.95:   10.835 ms/op
                 getUser·p0.99:   13.812 ms/op
                 getUser·p0.999:  16.292 ms/op
                 getUser·p0.9999: 16.761 ms/op
                 getUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5373
  mean =      6.059 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 9 
    [ 2.500,  3.750) = 377 
    [ 3.750,  5.000) = 1523 
    [ 5.000,  6.250) = 1647 
    [ 6.250,  7.500) = 852 
    [ 7.500,  8.750) = 371 
    [ 8.750, 10.000) = 228 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 139 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.819 ms/op
     p(50.0000) =      5.571 ms/op
     p(90.0000) =      9.044 ms/op
     p(95.0000) =     10.835 ms/op
     p(99.0000) =     13.812 ms/op
     p(99.9000) =     16.292 ms/op
     p(99.9900) =     16.761 ms/op
     p(99.9990) =     16.761 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 27.873 ±(99.9%) 1.403 ms/op
Iteration   1: 17.557 ±(99.9%) 0.429 ms/op
                 listUser·p0.00:   4.948 ms/op
                 listUser·p0.50:   16.679 ms/op
                 listUser·p0.90:   24.969 ms/op
                 listUser·p0.95:   27.656 ms/op
                 listUser·p0.99:   33.031 ms/op
                 listUser·p0.999:  38.514 ms/op
                 listUser·p0.9999: 39.059 ms/op
                 listUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1832
  mean =     17.557 ±(99.9%) 0.429 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 1 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 81 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 345 
    [15.000, 17.500) = 346 
    [17.500, 20.000) = 267 
    [20.000, 22.500) = 205 
    [22.500, 25.000) = 162 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      4.948 ms/op
     p(50.0000) =     16.679 ms/op
     p(90.0000) =     24.969 ms/op
     p(95.0000) =     27.656 ms/op
     p(99.0000) =     33.031 ms/op
     p(99.9000) =     38.514 ms/op
     p(99.9900) =     39.059 ms/op
     p(99.9990) =     39.059 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.936          ops/ms
Client.existUser                       thrpt          6.998          ops/ms
Client.getUser                         thrpt          4.924          ops/ms
Client.listUser                        thrpt          1.277          ops/ms
Client.createUser                       avgt          6.224           ms/op
Client.existUser                        avgt          3.864           ms/op
Client.getUser                          avgt          6.864           ms/op
Client.listUser                         avgt         23.305           ms/op
Client.createUser                     sample   6674   4.781 ± 0.172   ms/op
Client.createUser:createUser·p0.00    sample          0.877           ms/op
Client.createUser:createUser·p0.50    sample          3.774           ms/op
Client.createUser:createUser·p0.90    sample          6.341           ms/op
Client.createUser:createUser·p0.95    sample          7.752           ms/op
Client.createUser:createUser·p0.99    sample         15.843           ms/op
Client.createUser:createUser·p0.999   sample         53.608           ms/op
Client.createUser:createUser·p0.9999  sample         55.378           ms/op
Client.createUser:createUser·p1.00    sample         55.378           ms/op
Client.existUser                      sample  11239   2.929 ± 0.064   ms/op
Client.existUser:existUser·p0.00      sample          0.509           ms/op
Client.existUser:existUser·p0.50      sample          2.265           ms/op
Client.existUser:existUser·p0.90      sample          4.186           ms/op
Client.existUser:existUser·p0.95      sample          7.709           ms/op
Client.existUser:existUser·p0.99      sample         12.314           ms/op
Client.existUser:existUser·p0.999     sample         17.302           ms/op
Client.existUser:existUser·p0.9999    sample         17.400           ms/op
Client.existUser:existUser·p1.00      sample         17.400           ms/op
Client.getUser                        sample   5373   6.059 ± 0.099   ms/op
Client.getUser:getUser·p0.00          sample          1.819           ms/op
Client.getUser:getUser·p0.50          sample          5.571           ms/op
Client.getUser:getUser·p0.90          sample          9.044           ms/op
Client.getUser:getUser·p0.95          sample         10.835           ms/op
Client.getUser:getUser·p0.99          sample         13.812           ms/op
Client.getUser:getUser·p0.999         sample         16.292           ms/op
Client.getUser:getUser·p0.9999        sample         16.761           ms/op
Client.getUser:getUser·p1.00          sample         16.761           ms/op
Client.listUser                       sample   1832  17.557 ± 0.429   ms/op
Client.listUser:listUser·p0.00        sample          4.948           ms/op
Client.listUser:listUser·p0.50        sample         16.679           ms/op
Client.listUser:listUser·p0.90        sample         24.969           ms/op
Client.listUser:listUser·p0.95        sample         27.656           ms/op
Client.listUser:listUser·p0.99        sample         33.031           ms/op
Client.listUser:listUser·p0.999       sample         38.514           ms/op
Client.listUser:listUser·p0.9999      sample         39.059           ms/op
Client.listUser:listUser·p1.00        sample         39.059           ms/op
