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
# Warmup Iteration   1: 1.152 ops/ms
Iteration   1: 2.229 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.229 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.285 ops/ms
Iteration   1: 6.377 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.377 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.190 ops/ms
Iteration   1: 4.462 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.462 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.907 ops/ms
Iteration   1: 1.396 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.396 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 16.292 ±(99.9%) 0.254 ms/op
Iteration   1: 7.728 ±(99.9%) 0.057 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.728 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.965 ±(99.9%) 0.096 ms/op
Iteration   1: 4.112 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.112 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.604 ±(99.9%) 0.166 ms/op
Iteration   1: 5.129 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.129 ms/op


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
# Warmup Iteration   1: 27.321 ±(99.9%) 0.375 ms/op
Iteration   1: 18.801 ±(99.9%) 0.096 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.801 ms/op


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
# Warmup Iteration   1: 12.569 ±(99.9%) 0.390 ms/op
Iteration   1: 6.389 ±(99.9%) 0.137 ms/op
                 createUser·p0.00:   2.347 ms/op
                 createUser·p0.50:   6.865 ms/op
                 createUser·p0.90:   7.619 ms/op
                 createUser·p0.95:   7.827 ms/op
                 createUser·p0.99:   18.891 ms/op
                 createUser·p0.999:  30.489 ms/op
                 createUser·p0.9999: 30.835 ms/op
                 createUser·p1.00:   30.835 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5049
  mean =      6.389 ±(99.9%) 0.137 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 1339 
    [ 5.000,  7.500) = 2855 
    [ 7.500, 10.000) = 678 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.347 ms/op
     p(50.0000) =      6.865 ms/op
     p(90.0000) =      7.619 ms/op
     p(95.0000) =      7.827 ms/op
     p(99.0000) =     18.891 ms/op
     p(99.9000) =     30.489 ms/op
     p(99.9900) =     30.835 ms/op
     p(99.9990) =     30.835 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 7.619 ±(99.9%) 0.239 ms/op
Iteration   1: 4.064 ±(99.9%) 0.072 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.805 ms/op
                 existUser·p0.95:   5.923 ms/op
                 existUser·p0.99:   12.435 ms/op
                 existUser·p0.999:  23.003 ms/op
                 existUser·p0.9999: 23.626 ms/op
                 existUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7863
  mean =      4.064 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 546 
    [ 2.500,  5.000) = 6686 
    [ 5.000,  7.500) = 389 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.805 ms/op
     p(95.0000) =      5.923 ms/op
     p(99.0000) =     12.435 ms/op
     p(99.9000) =     23.003 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 11.325 ±(99.9%) 0.396 ms/op
Iteration   1: 4.816 ±(99.9%) 0.066 ms/op
                 getUser·p0.00:   1.593 ms/op
                 getUser·p0.50:   4.981 ms/op
                 getUser·p0.90:   5.759 ms/op
                 getUser·p0.95:   6.488 ms/op
                 getUser·p0.99:   11.685 ms/op
                 getUser·p0.999:  18.559 ms/op
                 getUser·p0.9999: 22.938 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6634
  mean =      4.816 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 159 
    [ 2.500,  5.000) = 3249 
    [ 5.000,  7.500) = 3006 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      4.981 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =      6.488 ms/op
     p(99.0000) =     11.685 ms/op
     p(99.9000) =     18.559 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 24.697 ±(99.9%) 0.832 ms/op
Iteration   1: 16.576 ±(99.9%) 0.204 ms/op
                 listUser·p0.00:   6.676 ms/op
                 listUser·p0.50:   16.810 ms/op
                 listUser·p0.90:   18.088 ms/op
                 listUser·p0.95:   21.194 ms/op
                 listUser·p0.99:   27.673 ms/op
                 listUser·p0.999:  30.227 ms/op
                 listUser·p0.9999: 30.507 ms/op
                 listUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1947
  mean =     16.576 ±(99.9%) 0.204 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 422 
    [15.000, 17.500) = 1085 
    [17.500, 20.000) = 252 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      6.676 ms/op
     p(50.0000) =     16.810 ms/op
     p(90.0000) =     18.088 ms/op
     p(95.0000) =     21.194 ms/op
     p(99.0000) =     27.673 ms/op
     p(99.9000) =     30.227 ms/op
     p(99.9900) =     30.507 ms/op
     p(99.9990) =     30.507 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.229          ops/ms
Client.existUser                       thrpt         6.377          ops/ms
Client.getUser                         thrpt         4.462          ops/ms
Client.listUser                        thrpt         1.396          ops/ms
Client.createUser                       avgt         7.728           ms/op
Client.existUser                        avgt         4.112           ms/op
Client.getUser                          avgt         5.129           ms/op
Client.listUser                         avgt        18.801           ms/op
Client.createUser                     sample  5049   6.389 ± 0.137   ms/op
Client.createUser:createUser·p0.00    sample         2.347           ms/op
Client.createUser:createUser·p0.50    sample         6.865           ms/op
Client.createUser:createUser·p0.90    sample         7.619           ms/op
Client.createUser:createUser·p0.95    sample         7.827           ms/op
Client.createUser:createUser·p0.99    sample        18.891           ms/op
Client.createUser:createUser·p0.999   sample        30.489           ms/op
Client.createUser:createUser·p0.9999  sample        30.835           ms/op
Client.createUser:createUser·p1.00    sample        30.835           ms/op
Client.existUser                      sample  7863   4.064 ± 0.072   ms/op
Client.existUser:existUser·p0.00      sample         0.853           ms/op
Client.existUser:existUser·p0.50      sample         3.756           ms/op
Client.existUser:existUser·p0.90      sample         4.805           ms/op
Client.existUser:existUser·p0.95      sample         5.923           ms/op
Client.existUser:existUser·p0.99      sample        12.435           ms/op
Client.existUser:existUser·p0.999     sample        23.003           ms/op
Client.existUser:existUser·p0.9999    sample        23.626           ms/op
Client.existUser:existUser·p1.00      sample        23.626           ms/op
Client.getUser                        sample  6634   4.816 ± 0.066   ms/op
Client.getUser:getUser·p0.00          sample         1.593           ms/op
Client.getUser:getUser·p0.50          sample         4.981           ms/op
Client.getUser:getUser·p0.90          sample         5.759           ms/op
Client.getUser:getUser·p0.95          sample         6.488           ms/op
Client.getUser:getUser·p0.99          sample        11.685           ms/op
Client.getUser:getUser·p0.999         sample        18.559           ms/op
Client.getUser:getUser·p0.9999        sample        22.938           ms/op
Client.getUser:getUser·p1.00          sample        22.938           ms/op
Client.listUser                       sample  1947  16.576 ± 0.204   ms/op
Client.listUser:listUser·p0.00        sample         6.676           ms/op
Client.listUser:listUser·p0.50        sample        16.810           ms/op
Client.listUser:listUser·p0.90        sample        18.088           ms/op
Client.listUser:listUser·p0.95        sample        21.194           ms/op
Client.listUser:listUser·p0.99        sample        27.673           ms/op
Client.listUser:listUser·p0.999       sample        30.227           ms/op
Client.listUser:listUser·p0.9999      sample        30.507           ms/op
Client.listUser:listUser·p1.00        sample        30.507           ms/op
