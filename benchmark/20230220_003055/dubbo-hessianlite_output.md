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
# Warmup Iteration   1: 0.970 ops/ms
Iteration   1: 2.235 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.235 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.155 ops/ms
Iteration   1: 5.725 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.725 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.984 ops/ms
Iteration   1: 4.109 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.109 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.801 ops/ms
Iteration   1: 1.270 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.270 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 18.661 ±(99.9%) 0.318 ms/op
Iteration   1: 10.438 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  10.438 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.746 ±(99.9%) 0.094 ms/op
Iteration   1: 3.819 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.819 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.172 ±(99.9%) 0.158 ms/op
Iteration   1: 5.008 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.008 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 35.610 ±(99.9%) 0.581 ms/op
Iteration   1: 21.934 ±(99.9%) 0.200 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  21.934 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 15.470 ±(99.9%) 0.536 ms/op
Iteration   1: 6.517 ±(99.9%) 0.171 ms/op
                 createUser·p0.00:   3.285 ms/op
                 createUser·p0.50:   5.677 ms/op
                 createUser·p0.90:   7.037 ms/op
                 createUser·p0.95:   9.708 ms/op
                 createUser·p0.99:   22.879 ms/op
                 createUser·p0.999:  39.846 ms/op
                 createUser·p0.9999: 39.911 ms/op
                 createUser·p1.00:   39.911 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4889
  mean =      6.517 ±(99.9%) 0.171 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 217 
    [ 5.000,  7.500) = 4360 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.285 ms/op
     p(50.0000) =      5.677 ms/op
     p(90.0000) =      7.037 ms/op
     p(95.0000) =      9.708 ms/op
     p(99.0000) =     22.879 ms/op
     p(99.9000) =     39.846 ms/op
     p(99.9900) =     39.911 ms/op
     p(99.9990) =     39.911 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.887 ±(99.9%) 0.227 ms/op
Iteration   1: 4.584 ±(99.9%) 0.048 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   4.407 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.718 ms/op
                 existUser·p0.99:   10.306 ms/op
                 existUser·p0.999:  16.155 ms/op
                 existUser·p0.9999: 16.663 ms/op
                 existUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6971
  mean =      4.584 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 49 
    [ 2.500,  3.750) = 475 
    [ 3.750,  5.000) = 5777 
    [ 5.000,  6.250) = 429 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     16.663 ms/op
     p(99.9990) =     16.663 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.290 ±(99.9%) 0.378 ms/op
Iteration   1: 4.898 ±(99.9%) 0.099 ms/op
                 getUser·p0.00:   0.578 ms/op
                 getUser·p0.50:   4.710 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   5.929 ms/op
                 getUser·p0.99:   18.670 ms/op
                 getUser·p0.999:  28.458 ms/op
                 getUser·p0.9999: 28.574 ms/op
                 getUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6524
  mean =      4.898 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 105 
    [ 2.500,  5.000) = 4735 
    [ 5.000,  7.500) = 1554 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.929 ms/op
     p(99.0000) =     18.670 ms/op
     p(99.9000) =     28.458 ms/op
     p(99.9900) =     28.574 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 29.781 ±(99.9%) 0.975 ms/op
Iteration   1: 19.653 ±(99.9%) 0.264 ms/op
                 listUser·p0.00:   10.961 ms/op
                 listUser·p0.50:   19.562 ms/op
                 listUser·p0.90:   21.791 ms/op
                 listUser·p0.95:   25.403 ms/op
                 listUser·p0.99:   30.368 ms/op
                 listUser·p0.999:  39.666 ms/op
                 listUser·p0.9999: 40.239 ms/op
                 listUser·p1.00:   40.239 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1624
  mean =     19.653 ±(99.9%) 0.264 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 344 
    [17.500, 20.000) = 458 
    [20.000, 22.500) = 642 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 5 
    [37.500, 40.000) = 2 
    [40.000, 42.500) = 1 
    [42.500, 45.000) = 0 
    [45.000, 47.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =     10.961 ms/op
     p(50.0000) =     19.562 ms/op
     p(90.0000) =     21.791 ms/op
     p(95.0000) =     25.403 ms/op
     p(99.0000) =     30.368 ms/op
     p(99.9000) =     39.666 ms/op
     p(99.9900) =     40.239 ms/op
     p(99.9990) =     40.239 ms/op
     p(99.9999) =     40.239 ms/op
    p(100.0000) =     40.239 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.235          ops/ms
Client.existUser                       thrpt         5.725          ops/ms
Client.getUser                         thrpt         4.109          ops/ms
Client.listUser                        thrpt         1.270          ops/ms
Client.createUser                       avgt        10.438           ms/op
Client.existUser                        avgt         3.819           ms/op
Client.getUser                          avgt         5.008           ms/op
Client.listUser                         avgt        21.934           ms/op
Client.createUser                     sample  4889   6.517 ± 0.171   ms/op
Client.createUser:createUser·p0.00    sample         3.285           ms/op
Client.createUser:createUser·p0.50    sample         5.677           ms/op
Client.createUser:createUser·p0.90    sample         7.037           ms/op
Client.createUser:createUser·p0.95    sample         9.708           ms/op
Client.createUser:createUser·p0.99    sample        22.879           ms/op
Client.createUser:createUser·p0.999   sample        39.846           ms/op
Client.createUser:createUser·p0.9999  sample        39.911           ms/op
Client.createUser:createUser·p1.00    sample        39.911           ms/op
Client.existUser                      sample  6971   4.584 ± 0.048   ms/op
Client.existUser:existUser·p0.00      sample         1.251           ms/op
Client.existUser:existUser·p0.50      sample         4.407           ms/op
Client.existUser:existUser·p0.90      sample         4.981           ms/op
Client.existUser:existUser·p0.95      sample         5.718           ms/op
Client.existUser:existUser·p0.99      sample        10.306           ms/op
Client.existUser:existUser·p0.999     sample        16.155           ms/op
Client.existUser:existUser·p0.9999    sample        16.663           ms/op
Client.existUser:existUser·p1.00      sample        16.663           ms/op
Client.getUser                        sample  6524   4.898 ± 0.099   ms/op
Client.getUser:getUser·p0.00          sample         0.578           ms/op
Client.getUser:getUser·p0.50          sample         4.710           ms/op
Client.getUser:getUser·p0.90          sample         5.390           ms/op
Client.getUser:getUser·p0.95          sample         5.929           ms/op
Client.getUser:getUser·p0.99          sample        18.670           ms/op
Client.getUser:getUser·p0.999         sample        28.458           ms/op
Client.getUser:getUser·p0.9999        sample        28.574           ms/op
Client.getUser:getUser·p1.00          sample        28.574           ms/op
Client.listUser                       sample  1624  19.653 ± 0.264   ms/op
Client.listUser:listUser·p0.00        sample        10.961           ms/op
Client.listUser:listUser·p0.50        sample        19.562           ms/op
Client.listUser:listUser·p0.90        sample        21.791           ms/op
Client.listUser:listUser·p0.95        sample        25.403           ms/op
Client.listUser:listUser·p0.99        sample        30.368           ms/op
Client.listUser:listUser·p0.999       sample        39.666           ms/op
Client.listUser:listUser·p0.9999      sample        40.239           ms/op
Client.listUser:listUser·p1.00        sample        40.239           ms/op
