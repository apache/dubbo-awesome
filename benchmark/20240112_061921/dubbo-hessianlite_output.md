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
# Warmup Iteration   1: 2.337 ops/ms
Iteration   1: 6.340 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.340 ops/ms


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
# Warmup Iteration   1: 5.794 ops/ms
Iteration   1: 12.621 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.621 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ops/ms
Iteration   1: 7.606 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.606 ops/ms


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
# Warmup Iteration   1: 2.283 ops/ms
Iteration   1: 3.570 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.570 ops/ms


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
# Warmup Iteration   1: 5.966 ±(99.9%) 0.105 ms/op
Iteration   1: 3.210 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.210 ms/op


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
# Warmup Iteration   1: 3.085 ±(99.9%) 0.035 ms/op
Iteration   1: 1.973 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.973 ms/op


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
# Warmup Iteration   1: 5.475 ±(99.9%) 0.096 ms/op
Iteration   1: 2.927 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.927 ms/op


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
# Warmup Iteration   1: 13.432 ±(99.9%) 0.369 ms/op
Iteration   1: 8.017 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.017 ms/op


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
# Warmup Iteration   1: 4.947 ±(99.9%) 0.109 ms/op
Iteration   1: 3.293 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   6.063 ms/op
                 createUser·p0.999:  21.430 ms/op
                 createUser·p0.9999: 21.561 ms/op
                 createUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9789
  mean =      3.293 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 904 
    [ 2.500,  5.000) = 8667 
    [ 5.000,  7.500) = 148 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.063 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 3.367 ±(99.9%) 0.088 ms/op
Iteration   1: 2.134 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   2.066 ms/op
                 existUser·p0.90:   2.576 ms/op
                 existUser·p0.95:   2.793 ms/op
                 existUser·p0.99:   3.392 ms/op
                 existUser·p0.999:  19.104 ms/op
                 existUser·p0.9999: 19.186 ms/op
                 existUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14998
  mean =      2.134 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 378 
    [ 1.250,  2.500) = 12677 
    [ 2.500,  3.750) = 1839 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      3.392 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     19.186 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.131 ms/op
Iteration   1: 3.877 ±(99.9%) 0.280 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   4.108 ms/op
                 getUser·p0.95:   4.508 ms/op
                 getUser·p0.99:   28.290 ms/op
                 getUser·p0.999:  106.737 ms/op
                 getUser·p0.9999: 112.853 ms/op
                 getUser·p1.00:   112.853 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8332
  mean =      3.877 ±(99.9%) 0.280 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 8221 
    [ 12.500,  25.000) = 21 
    [ 25.000,  37.500) = 21 
    [ 37.500,  50.000) = 5 
    [ 50.000,  62.500) = 3 
    [ 62.500,  75.000) = 13 
    [ 75.000,  87.500) = 14 
    [ 87.500, 100.000) = 18 
    [100.000, 112.500) = 14 
    [112.500, 125.000) = 2 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.508 ms/op
     p(99.0000) =     28.290 ms/op
     p(99.9000) =    106.737 ms/op
     p(99.9900) =    112.853 ms/op
     p(99.9990) =    112.853 ms/op
     p(99.9999) =    112.853 ms/op
    p(100.0000) =    112.853 ms/op


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
# Warmup Iteration   1: 11.583 ±(99.9%) 0.480 ms/op
Iteration   1: 7.812 ±(99.9%) 0.109 ms/op
                 listUser·p0.00:   3.154 ms/op
                 listUser·p0.50:   7.504 ms/op
                 listUser·p0.90:   9.994 ms/op
                 listUser·p0.95:   11.420 ms/op
                 listUser·p0.99:   15.580 ms/op
                 listUser·p0.999:  20.604 ms/op
                 listUser·p0.9999: 25.854 ms/op
                 listUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4093
  mean =      7.812 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 145 
    [ 5.000,  7.500) = 1896 
    [ 7.500, 10.000) = 1644 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.154 ms/op
     p(50.0000) =      7.504 ms/op
     p(90.0000) =      9.994 ms/op
     p(95.0000) =     11.420 ms/op
     p(99.0000) =     15.580 ms/op
     p(99.9000) =     20.604 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     25.854 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           6.340          ops/ms
Client.existUser                       thrpt          12.621          ops/ms
Client.getUser                         thrpt           7.606          ops/ms
Client.listUser                        thrpt           3.570          ops/ms
Client.createUser                       avgt           3.210           ms/op
Client.existUser                        avgt           1.973           ms/op
Client.getUser                          avgt           2.927           ms/op
Client.listUser                         avgt           8.017           ms/op
Client.createUser                     sample   9789    3.293 ± 0.045   ms/op
Client.createUser:createUser·p0.00    sample           1.073           ms/op
Client.createUser:createUser·p0.50    sample           3.121           ms/op
Client.createUser:createUser·p0.90    sample           4.108           ms/op
Client.createUser:createUser·p0.95    sample           4.579           ms/op
Client.createUser:createUser·p0.99    sample           6.063           ms/op
Client.createUser:createUser·p0.999   sample          21.430           ms/op
Client.createUser:createUser·p0.9999  sample          21.561           ms/op
Client.createUser:createUser·p1.00    sample          21.561           ms/op
Client.existUser                      sample  14998    2.134 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample           0.547           ms/op
Client.existUser:existUser·p0.50      sample           2.066           ms/op
Client.existUser:existUser·p0.90      sample           2.576           ms/op
Client.existUser:existUser·p0.95      sample           2.793           ms/op
Client.existUser:existUser·p0.99      sample           3.392           ms/op
Client.existUser:existUser·p0.999     sample          19.104           ms/op
Client.existUser:existUser·p0.9999    sample          19.186           ms/op
Client.existUser:existUser·p1.00      sample          19.202           ms/op
Client.getUser                        sample   8332    3.877 ± 0.280   ms/op
Client.getUser:getUser·p0.00          sample           0.805           ms/op
Client.getUser:getUser·p0.50          sample           3.047           ms/op
Client.getUser:getUser·p0.90          sample           4.108           ms/op
Client.getUser:getUser·p0.95          sample           4.508           ms/op
Client.getUser:getUser·p0.99          sample          28.290           ms/op
Client.getUser:getUser·p0.999         sample         106.737           ms/op
Client.getUser:getUser·p0.9999        sample         112.853           ms/op
Client.getUser:getUser·p1.00          sample         112.853           ms/op
Client.listUser                       sample   4093    7.812 ± 0.109   ms/op
Client.listUser:listUser·p0.00        sample           3.154           ms/op
Client.listUser:listUser·p0.50        sample           7.504           ms/op
Client.listUser:listUser·p0.90        sample           9.994           ms/op
Client.listUser:listUser·p0.95        sample          11.420           ms/op
Client.listUser:listUser·p0.99        sample          15.580           ms/op
Client.listUser:listUser·p0.999       sample          20.604           ms/op
Client.listUser:listUser·p0.9999      sample          25.854           ms/op
Client.listUser:listUser·p1.00        sample          25.854           ms/op
