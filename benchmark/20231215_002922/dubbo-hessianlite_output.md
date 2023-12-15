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
# Warmup Iteration   1: 2.461 ops/ms
Iteration   1: 6.468 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.468 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.169 ops/ms
Iteration   1: 13.004 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.004 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.688 ops/ms
Iteration   1: 8.944 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.944 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.463 ops/ms
Iteration   1: 4.081 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.081 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.449 ±(99.9%) 0.090 ms/op
Iteration   1: 3.093 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.093 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.224 ±(99.9%) 0.034 ms/op
Iteration   1: 1.965 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.965 ms/op


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.043 ms/op
Iteration   1: 2.774 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.774 ms/op


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
# Warmup Iteration   1: 12.135 ±(99.9%) 0.299 ms/op
Iteration   1: 8.670 ±(99.9%) 0.171 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.670 ms/op


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
# Warmup Iteration   1: 5.000 ±(99.9%) 0.110 ms/op
Iteration   1: 3.069 ±(99.9%) 0.066 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.810 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   9.452 ms/op
                 createUser·p0.999:  33.325 ms/op
                 createUser·p0.9999: 34.531 ms/op
                 createUser·p1.00:   34.537 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10506
  mean =      3.069 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2383 
    [ 2.500,  5.000) = 7787 
    [ 5.000,  7.500) = 218 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      9.452 ms/op
     p(99.9000) =     33.325 ms/op
     p(99.9900) =     34.531 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.077 ms/op
Iteration   1: 1.981 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.589 ms/op
                 existUser·p0.50:   1.837 ms/op
                 existUser·p0.90:   2.662 ms/op
                 existUser·p0.95:   2.957 ms/op
                 existUser·p0.99:   3.392 ms/op
                 existUser·p0.999:  4.192 ms/op
                 existUser·p0.9999: 6.370 ms/op
                 existUser·p1.00:   6.447 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16294
  mean =      1.981 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 17 
    [1.000, 1.500) = 506 
    [1.500, 2.000) = 10778 
    [2.000, 2.500) = 2745 
    [2.500, 3.000) = 1560 
    [3.000, 3.500) = 588 
    [3.500, 4.000) = 78 
    [4.000, 4.500) = 11 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      3.392 ms/op
     p(99.9000) =      4.192 ms/op
     p(99.9900) =      6.370 ms/op
     p(99.9990) =      6.447 ms/op
     p(99.9999) =      6.447 ms/op
    p(100.0000) =      6.447 ms/op


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.181 ms/op
Iteration   1: 3.371 ±(99.9%) 0.064 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.297 ms/op
                 getUser·p0.999:  32.735 ms/op
                 getUser·p0.9999: 32.866 ms/op
                 getUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9515
  mean =      3.371 ±(99.9%) 0.064 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1022 
    [ 2.500,  5.000) = 8253 
    [ 5.000,  7.500) = 174 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      6.297 ms/op
     p(99.9000) =     32.735 ms/op
     p(99.9900) =     32.866 ms/op
     p(99.9990) =     32.866 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


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
# Warmup Iteration   1: 12.370 ±(99.9%) 0.390 ms/op
Iteration   1: 8.562 ±(99.9%) 0.158 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   8.159 ms/op
                 listUser·p0.90:   12.157 ms/op
                 listUser·p0.95:   13.451 ms/op
                 listUser·p0.99:   18.907 ms/op
                 listUser·p0.999:  24.875 ms/op
                 listUser·p0.9999: 50.463 ms/op
                 listUser·p1.00:   50.463 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3865
  mean =      8.562 ±(99.9%) 0.158 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 330 
    [ 5.000, 10.000) = 2533 
    [10.000, 15.000) = 908 
    [15.000, 20.000) = 77 
    [20.000, 25.000) = 15 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      8.159 ms/op
     p(90.0000) =     12.157 ms/op
     p(95.0000) =     13.451 ms/op
     p(99.0000) =     18.907 ms/op
     p(99.9000) =     24.875 ms/op
     p(99.9900) =     50.463 ms/op
     p(99.9990) =     50.463 ms/op
     p(99.9999) =     50.463 ms/op
    p(100.0000) =     50.463 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.468          ops/ms
Client.existUser                       thrpt         13.004          ops/ms
Client.getUser                         thrpt          8.944          ops/ms
Client.listUser                        thrpt          4.081          ops/ms
Client.createUser                       avgt          3.093           ms/op
Client.existUser                        avgt          1.965           ms/op
Client.getUser                          avgt          2.774           ms/op
Client.listUser                         avgt          8.670           ms/op
Client.createUser                     sample  10506   3.069 ± 0.066   ms/op
Client.createUser:createUser·p0.00    sample          0.954           ms/op
Client.createUser:createUser·p0.50    sample          2.810           ms/op
Client.createUser:createUser·p0.90    sample          3.596           ms/op
Client.createUser:createUser·p0.95    sample          4.293           ms/op
Client.createUser:createUser·p0.99    sample          9.452           ms/op
Client.createUser:createUser·p0.999   sample         33.325           ms/op
Client.createUser:createUser·p0.9999  sample         34.531           ms/op
Client.createUser:createUser·p1.00    sample         34.537           ms/op
Client.existUser                      sample  16294   1.981 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.589           ms/op
Client.existUser:existUser·p0.50      sample          1.837           ms/op
Client.existUser:existUser·p0.90      sample          2.662           ms/op
Client.existUser:existUser·p0.95      sample          2.957           ms/op
Client.existUser:existUser·p0.99      sample          3.392           ms/op
Client.existUser:existUser·p0.999     sample          4.192           ms/op
Client.existUser:existUser·p0.9999    sample          6.370           ms/op
Client.existUser:existUser·p1.00      sample          6.447           ms/op
Client.getUser                        sample   9515   3.371 ± 0.064   ms/op
Client.getUser:getUser·p0.00          sample          0.830           ms/op
Client.getUser:getUser·p0.50          sample          3.219           ms/op
Client.getUser:getUser·p0.90          sample          4.067           ms/op
Client.getUser:getUser·p0.95          sample          4.481           ms/op
Client.getUser:getUser·p0.99          sample          6.297           ms/op
Client.getUser:getUser·p0.999         sample         32.735           ms/op
Client.getUser:getUser·p0.9999        sample         32.866           ms/op
Client.getUser:getUser·p1.00          sample         32.866           ms/op
Client.listUser                       sample   3865   8.562 ± 0.158   ms/op
Client.listUser:listUser·p0.00        sample          1.157           ms/op
Client.listUser:listUser·p0.50        sample          8.159           ms/op
Client.listUser:listUser·p0.90        sample         12.157           ms/op
Client.listUser:listUser·p0.95        sample         13.451           ms/op
Client.listUser:listUser·p0.99        sample         18.907           ms/op
Client.listUser:listUser·p0.999       sample         24.875           ms/op
Client.listUser:listUser·p0.9999      sample         50.463           ms/op
Client.listUser:listUser·p1.00        sample         50.463           ms/op
