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
# Warmup Iteration   1: 0.709 ops/ms
Iteration   1: 1.582 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.582 ops/ms


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
# Warmup Iteration   1: 1.776 ops/ms
Iteration   1: 5.363 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.363 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.318 ops/ms
Iteration   1: 3.894 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.894 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 0.719 ops/ms
Iteration   1: 0.944 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.944 ops/ms


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
# Warmup Iteration   1: 22.109 ±(99.9%) 0.486 ms/op
Iteration   1: 10.665 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  10.665 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 12.987 ±(99.9%) 0.219 ms/op
Iteration   1: 5.446 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.446 ms/op


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
# Warmup Iteration   1: 14.193 ±(99.9%) 0.253 ms/op
Iteration   1: 5.490 ±(99.9%) 0.048 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.490 ms/op


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
# Warmup Iteration   1: 34.254 ±(99.9%) 0.727 ms/op
Iteration   1: 21.812 ±(99.9%) 0.082 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  21.812 ms/op


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
# Warmup Iteration   1: 16.415 ±(99.9%) 0.506 ms/op
Iteration   1: 10.029 ±(99.9%) 0.247 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   8.946 ms/op
                 createUser·p0.90:   13.337 ms/op
                 createUser·p0.95:   20.796 ms/op
                 createUser·p0.99:   29.295 ms/op
                 createUser·p0.999:  39.041 ms/op
                 createUser·p0.9999: 40.763 ms/op
                 createUser·p1.00:   40.763 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3206
  mean =     10.029 ±(99.9%) 0.247 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 55 
    [ 5.000, 10.000) = 2591 
    [10.000, 15.000) = 282 
    [15.000, 20.000) = 109 
    [20.000, 25.000) = 111 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      8.946 ms/op
     p(90.0000) =     13.337 ms/op
     p(95.0000) =     20.796 ms/op
     p(99.0000) =     29.295 ms/op
     p(99.9000) =     39.041 ms/op
     p(99.9900) =     40.763 ms/op
     p(99.9990) =     40.763 ms/op
     p(99.9999) =     40.763 ms/op
    p(100.0000) =     40.763 ms/op


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
# Warmup Iteration   1: 10.585 ±(99.9%) 0.294 ms/op
Iteration   1: 5.535 ±(99.9%) 0.117 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   5.636 ms/op
                 existUser·p0.90:   6.603 ms/op
                 existUser·p0.95:   6.941 ms/op
                 existUser·p0.99:   14.418 ms/op
                 existUser·p0.999:  32.972 ms/op
                 existUser·p0.9999: 33.948 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 5776
  mean =      5.535 ±(99.9%) 0.117 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 143 
    [ 2.500,  5.000) = 2143 
    [ 5.000,  7.500) = 3260 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      5.636 ms/op
     p(90.0000) =      6.603 ms/op
     p(95.0000) =      6.941 ms/op
     p(99.0000) =     14.418 ms/op
     p(99.9000) =     32.972 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 15.239 ±(99.9%) 0.474 ms/op
Iteration   1: 6.344 ±(99.9%) 0.105 ms/op
                 getUser·p0.00:   2.077 ms/op
                 getUser·p0.50:   5.915 ms/op
                 getUser·p0.90:   8.008 ms/op
                 getUser·p0.95:   9.519 ms/op
                 getUser·p0.99:   13.654 ms/op
                 getUser·p0.999:  26.313 ms/op
                 getUser·p0.9999: 28.180 ms/op
                 getUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5163
  mean =      6.344 ±(99.9%) 0.105 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 1216 
    [ 5.000,  7.500) = 3057 
    [ 7.500, 10.000) = 659 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.077 ms/op
     p(50.0000) =      5.915 ms/op
     p(90.0000) =      8.008 ms/op
     p(95.0000) =      9.519 ms/op
     p(99.0000) =     13.654 ms/op
     p(99.9000) =     26.313 ms/op
     p(99.9900) =     28.180 ms/op
     p(99.9990) =     28.180 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 33.382 ±(99.9%) 1.192 ms/op
Iteration   1: 21.415 ±(99.9%) 0.551 ms/op
                 listUser·p0.00:   7.692 ms/op
                 listUser·p0.50:   19.857 ms/op
                 listUser·p0.90:   30.671 ms/op
                 listUser·p0.95:   31.195 ms/op
                 listUser·p0.99:   33.181 ms/op
                 listUser·p0.999:  36.005 ms/op
                 listUser·p0.9999: 37.421 ms/op
                 listUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1479
  mean =     21.415 ±(99.9%) 0.551 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 243 
    [15.000, 17.500) = 242 
    [17.500, 20.000) = 196 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 197 
    [27.500, 30.000) = 156 
    [30.000, 32.500) = 147 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      7.692 ms/op
     p(50.0000) =     19.857 ms/op
     p(90.0000) =     30.671 ms/op
     p(95.0000) =     31.195 ms/op
     p(99.0000) =     33.181 ms/op
     p(99.9000) =     36.005 ms/op
     p(99.9900) =     37.421 ms/op
     p(99.9990) =     37.421 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# Run complete. Total time: 00:01:29

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.582          ops/ms
Client.existUser                       thrpt         5.363          ops/ms
Client.getUser                         thrpt         3.894          ops/ms
Client.listUser                        thrpt         0.944          ops/ms
Client.createUser                       avgt        10.665           ms/op
Client.existUser                        avgt         5.446           ms/op
Client.getUser                          avgt         5.490           ms/op
Client.listUser                         avgt        21.812           ms/op
Client.createUser                     sample  3206  10.029 ± 0.247   ms/op
Client.createUser:createUser·p0.00    sample         0.782           ms/op
Client.createUser:createUser·p0.50    sample         8.946           ms/op
Client.createUser:createUser·p0.90    sample        13.337           ms/op
Client.createUser:createUser·p0.95    sample        20.796           ms/op
Client.createUser:createUser·p0.99    sample        29.295           ms/op
Client.createUser:createUser·p0.999   sample        39.041           ms/op
Client.createUser:createUser·p0.9999  sample        40.763           ms/op
Client.createUser:createUser·p1.00    sample        40.763           ms/op
Client.existUser                      sample  5776   5.535 ± 0.117   ms/op
Client.existUser:existUser·p0.00      sample         1.233           ms/op
Client.existUser:existUser·p0.50      sample         5.636           ms/op
Client.existUser:existUser·p0.90      sample         6.603           ms/op
Client.existUser:existUser·p0.95      sample         6.941           ms/op
Client.existUser:existUser·p0.99      sample        14.418           ms/op
Client.existUser:existUser·p0.999     sample        32.972           ms/op
Client.existUser:existUser·p0.9999    sample        33.948           ms/op
Client.existUser:existUser·p1.00      sample        33.948           ms/op
Client.getUser                        sample  5163   6.344 ± 0.105   ms/op
Client.getUser:getUser·p0.00          sample         2.077           ms/op
Client.getUser:getUser·p0.50          sample         5.915           ms/op
Client.getUser:getUser·p0.90          sample         8.008           ms/op
Client.getUser:getUser·p0.95          sample         9.519           ms/op
Client.getUser:getUser·p0.99          sample        13.654           ms/op
Client.getUser:getUser·p0.999         sample        26.313           ms/op
Client.getUser:getUser·p0.9999        sample        28.180           ms/op
Client.getUser:getUser·p1.00          sample        28.180           ms/op
Client.listUser                       sample  1479  21.415 ± 0.551   ms/op
Client.listUser:listUser·p0.00        sample         7.692           ms/op
Client.listUser:listUser·p0.50        sample        19.857           ms/op
Client.listUser:listUser·p0.90        sample        30.671           ms/op
Client.listUser:listUser·p0.95        sample        31.195           ms/op
Client.listUser:listUser·p0.99        sample        33.181           ms/op
Client.listUser:listUser·p0.999       sample        36.005           ms/op
Client.listUser:listUser·p0.9999      sample        37.421           ms/op
Client.listUser:listUser·p1.00        sample        37.421           ms/op
