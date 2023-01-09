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
# Warmup Iteration   1: 1.018 ops/ms
Iteration   1: 3.101 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.101 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.816 ops/ms
Iteration   1: 8.586 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  8.586 ops/ms


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
# Warmup Iteration   1: 1.577 ops/ms
Iteration   1: 3.722 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.722 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.768 ops/ms
Iteration   1: 1.311 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.311 ops/ms


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
# Warmup Iteration   1: 18.638 ±(99.9%) 0.271 ms/op
Iteration   1: 9.219 ±(99.9%) 0.044 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.219 ms/op


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
# Warmup Iteration   1: 7.219 ±(99.9%) 0.109 ms/op
Iteration   1: 3.332 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.332 ms/op


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
# Warmup Iteration   1: 9.973 ±(99.9%) 0.143 ms/op
Iteration   1: 4.488 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.488 ms/op


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
# Warmup Iteration   1: 26.627 ±(99.9%) 0.543 ms/op
Iteration   1: 16.937 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.937 ms/op


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
# Warmup Iteration   1: 12.733 ±(99.9%) 0.426 ms/op
Iteration   1: 6.546 ±(99.9%) 0.103 ms/op
                 createUser·p0.00:   2.753 ms/op
                 createUser·p0.50:   6.005 ms/op
                 createUser·p0.90:   6.865 ms/op
                 createUser·p0.95:   11.303 ms/op
                 createUser·p0.99:   18.037 ms/op
                 createUser·p0.999:  21.006 ms/op
                 createUser·p0.9999: 21.135 ms/op
                 createUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4953
  mean =      6.546 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 83 
    [ 5.000,  7.500) = 4513 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.753 ms/op
     p(50.0000) =      6.005 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =     11.303 ms/op
     p(99.0000) =     18.037 ms/op
     p(99.9000) =     21.006 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 6.764 ±(99.9%) 0.207 ms/op
Iteration   1: 3.636 ±(99.9%) 0.062 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   10.306 ms/op
                 existUser·p0.999:  27.132 ms/op
                 existUser·p0.9999: 27.525 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8800
  mean =      3.636 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 409 
    [ 2.500,  5.000) = 8025 
    [ 5.000,  7.500) = 142 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =     10.306 ms/op
     p(99.9000) =     27.132 ms/op
     p(99.9900) =     27.525 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 8.373 ±(99.9%) 0.231 ms/op
Iteration   1: 4.296 ±(99.9%) 0.065 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   7.216 ms/op
                 getUser·p0.99:   11.846 ms/op
                 getUser·p0.999:  16.589 ms/op
                 getUser·p0.9999: 17.007 ms/op
                 getUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7462
  mean =      4.296 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 140 
    [ 2.500,  3.750) = 2650 
    [ 3.750,  5.000) = 3653 
    [ 5.000,  6.250) = 528 
    [ 6.250,  7.500) = 133 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      7.216 ms/op
     p(99.0000) =     11.846 ms/op
     p(99.9000) =     16.589 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     17.007 ms/op
     p(99.9999) =     17.007 ms/op
    p(100.0000) =     17.007 ms/op


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
# Warmup Iteration   1: 24.484 ±(99.9%) 0.573 ms/op
Iteration   1: 14.719 ±(99.9%) 0.145 ms/op
                 listUser·p0.00:   9.306 ms/op
                 listUser·p0.50:   14.098 ms/op
                 listUser·p0.90:   16.160 ms/op
                 listUser·p0.95:   17.007 ms/op
                 listUser·p0.99:   25.506 ms/op
                 listUser·p0.999:  31.570 ms/op
                 listUser·p0.9999: 31.588 ms/op
                 listUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2186
  mean =     14.719 ±(99.9%) 0.145 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 1411 
    [15.000, 17.500) = 633 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      9.306 ms/op
     p(50.0000) =     14.098 ms/op
     p(90.0000) =     16.160 ms/op
     p(95.0000) =     17.007 ms/op
     p(99.0000) =     25.506 ms/op
     p(99.9000) =     31.570 ms/op
     p(99.9900) =     31.588 ms/op
     p(99.9990) =     31.588 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.101          ops/ms
Client.existUser                       thrpt         8.586          ops/ms
Client.getUser                         thrpt         3.722          ops/ms
Client.listUser                        thrpt         1.311          ops/ms
Client.createUser                       avgt         9.219           ms/op
Client.existUser                        avgt         3.332           ms/op
Client.getUser                          avgt         4.488           ms/op
Client.listUser                         avgt        16.937           ms/op
Client.createUser                     sample  4953   6.546 ± 0.103   ms/op
Client.createUser:createUser·p0.00    sample         2.753           ms/op
Client.createUser:createUser·p0.50    sample         6.005           ms/op
Client.createUser:createUser·p0.90    sample         6.865           ms/op
Client.createUser:createUser·p0.95    sample        11.303           ms/op
Client.createUser:createUser·p0.99    sample        18.037           ms/op
Client.createUser:createUser·p0.999   sample        21.006           ms/op
Client.createUser:createUser·p0.9999  sample        21.135           ms/op
Client.createUser:createUser·p1.00    sample        21.135           ms/op
Client.existUser                      sample  8800   3.636 ± 0.062   ms/op
Client.existUser:existUser·p0.00      sample         0.779           ms/op
Client.existUser:existUser·p0.50      sample         3.428           ms/op
Client.existUser:existUser·p0.90      sample         3.817           ms/op
Client.existUser:existUser·p0.95      sample         4.841           ms/op
Client.existUser:existUser·p0.99      sample        10.306           ms/op
Client.existUser:existUser·p0.999     sample        27.132           ms/op
Client.existUser:existUser·p0.9999    sample        27.525           ms/op
Client.existUser:existUser·p1.00      sample        27.525           ms/op
Client.getUser                        sample  7462   4.296 ± 0.065   ms/op
Client.getUser:getUser·p0.00          sample         1.632           ms/op
Client.getUser:getUser·p0.50          sample         4.047           ms/op
Client.getUser:getUser·p0.90          sample         5.448           ms/op
Client.getUser:getUser·p0.95          sample         7.216           ms/op
Client.getUser:getUser·p0.99          sample        11.846           ms/op
Client.getUser:getUser·p0.999         sample        16.589           ms/op
Client.getUser:getUser·p0.9999        sample        17.007           ms/op
Client.getUser:getUser·p1.00          sample        17.007           ms/op
Client.listUser                       sample  2186  14.719 ± 0.145   ms/op
Client.listUser:listUser·p0.00        sample         9.306           ms/op
Client.listUser:listUser·p0.50        sample        14.098           ms/op
Client.listUser:listUser·p0.90        sample        16.160           ms/op
Client.listUser:listUser·p0.95        sample        17.007           ms/op
Client.listUser:listUser·p0.99        sample        25.506           ms/op
Client.listUser:listUser·p0.999       sample        31.570           ms/op
Client.listUser:listUser·p0.9999      sample        31.588           ms/op
Client.listUser:listUser·p1.00        sample        31.588           ms/op
