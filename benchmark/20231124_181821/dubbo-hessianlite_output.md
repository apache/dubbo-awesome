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
# Warmup Iteration   1: 2.458 ops/ms
Iteration   1: 6.072 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.072 ops/ms


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
# Warmup Iteration   1: 6.224 ops/ms
Iteration   1: 16.689 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  16.689 ops/ms


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
# Warmup Iteration   1: 4.291 ops/ms
Iteration   1: 8.470 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.470 ops/ms


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
# Warmup Iteration   1: 2.511 ops/ms
Iteration   1: 3.737 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.737 ops/ms


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.069 ms/op
Iteration   1: 3.055 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.055 ms/op


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
# Warmup Iteration   1: 2.841 ±(99.9%) 0.034 ms/op
Iteration   1: 1.755 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.755 ms/op


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
# Warmup Iteration   1: 4.241 ±(99.9%) 0.058 ms/op
Iteration   1: 2.885 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.885 ms/op


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
# Warmup Iteration   1: 11.529 ±(99.9%) 0.279 ms/op
Iteration   1: 8.123 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.123 ms/op


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
# Warmup Iteration   1: 5.108 ±(99.9%) 0.117 ms/op
Iteration   1: 3.008 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   2.740 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   10.371 ms/op
                 createUser·p0.999:  22.446 ms/op
                 createUser·p0.9999: 23.249 ms/op
                 createUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10633
  mean =      3.008 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3491 
    [ 2.500,  5.000) = 6894 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =     10.371 ms/op
     p(99.9000) =     22.446 ms/op
     p(99.9900) =     23.249 ms/op
     p(99.9990) =     23.265 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 2.717 ±(99.9%) 0.045 ms/op
Iteration   1: 1.783 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.291 ms/op
                 existUser·p0.50:   1.683 ms/op
                 existUser·p0.90:   2.163 ms/op
                 existUser·p0.95:   2.339 ms/op
                 existUser·p0.99:   3.225 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 11.476 ms/op
                 existUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17926
  mean =      1.783 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 472 
    [ 1.250,  2.500) = 16960 
    [ 2.500,  3.750) = 372 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.291 ms/op
     p(50.0000) =      1.683 ms/op
     p(90.0000) =      2.163 ms/op
     p(95.0000) =      2.339 ms/op
     p(99.0000) =      3.225 ms/op
     p(99.9000) =     11.207 ms/op
     p(99.9900) =     11.476 ms/op
     p(99.9990) =     11.502 ms/op
     p(99.9999) =     11.502 ms/op
    p(100.0000) =     11.502 ms/op


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
# Warmup Iteration   1: 4.637 ±(99.9%) 0.170 ms/op
Iteration   1: 2.944 ±(99.9%) 0.052 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.814 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   7.397 ms/op
                 getUser·p0.999:  26.378 ms/op
                 getUser·p0.9999: 26.891 ms/op
                 getUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10910
  mean =      2.944 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3778 
    [ 2.500,  5.000) = 6928 
    [ 5.000,  7.500) = 97 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     26.378 ms/op
     p(99.9900) =     26.891 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 11.180 ±(99.9%) 0.328 ms/op
Iteration   1: 7.686 ±(99.9%) 0.130 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   7.340 ms/op
                 listUser·p0.90:   10.125 ms/op
                 listUser·p0.95:   11.561 ms/op
                 listUser·p0.99:   16.700 ms/op
                 listUser·p0.999:  26.941 ms/op
                 listUser·p0.9999: 28.213 ms/op
                 listUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4166
  mean =      7.686 ±(99.9%) 0.130 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 236 
    [ 5.000,  7.500) = 1991 
    [ 7.500, 10.000) = 1486 
    [10.000, 12.500) = 343 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.261 ms/op
     p(50.0000) =      7.340 ms/op
     p(90.0000) =     10.125 ms/op
     p(95.0000) =     11.561 ms/op
     p(99.0000) =     16.700 ms/op
     p(99.9000) =     26.941 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     28.213 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.072          ops/ms
Client.existUser                       thrpt         16.689          ops/ms
Client.getUser                         thrpt          8.470          ops/ms
Client.listUser                        thrpt          3.737          ops/ms
Client.createUser                       avgt          3.055           ms/op
Client.existUser                        avgt          1.755           ms/op
Client.getUser                          avgt          2.885           ms/op
Client.listUser                         avgt          8.123           ms/op
Client.createUser                     sample  10633   3.008 ± 0.052   ms/op
Client.createUser:createUser·p0.00    sample          1.036           ms/op
Client.createUser:createUser·p0.50    sample          2.740           ms/op
Client.createUser:createUser·p0.90    sample          3.666           ms/op
Client.createUser:createUser·p0.95    sample          3.990           ms/op
Client.createUser:createUser·p0.99    sample         10.371           ms/op
Client.createUser:createUser·p0.999   sample         22.446           ms/op
Client.createUser:createUser·p0.9999  sample         23.249           ms/op
Client.createUser:createUser·p1.00    sample         23.265           ms/op
Client.existUser                      sample  17926   1.783 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.291           ms/op
Client.existUser:existUser·p0.50      sample          1.683           ms/op
Client.existUser:existUser·p0.90      sample          2.163           ms/op
Client.existUser:existUser·p0.95      sample          2.339           ms/op
Client.existUser:existUser·p0.99      sample          3.225           ms/op
Client.existUser:existUser·p0.999     sample         11.207           ms/op
Client.existUser:existUser·p0.9999    sample         11.476           ms/op
Client.existUser:existUser·p1.00      sample         11.502           ms/op
Client.getUser                        sample  10910   2.944 ± 0.052   ms/op
Client.getUser:getUser·p0.00          sample          1.010           ms/op
Client.getUser:getUser·p0.50          sample          2.814           ms/op
Client.getUser:getUser·p0.90          sample          3.703           ms/op
Client.getUser:getUser·p0.95          sample          4.055           ms/op
Client.getUser:getUser·p0.99          sample          7.397           ms/op
Client.getUser:getUser·p0.999         sample         26.378           ms/op
Client.getUser:getUser·p0.9999        sample         26.891           ms/op
Client.getUser:getUser·p1.00          sample         26.903           ms/op
Client.listUser                       sample   4166   7.686 ± 0.130   ms/op
Client.listUser:listUser·p0.00        sample          2.261           ms/op
Client.listUser:listUser·p0.50        sample          7.340           ms/op
Client.listUser:listUser·p0.90        sample         10.125           ms/op
Client.listUser:listUser·p0.95        sample         11.561           ms/op
Client.listUser:listUser·p0.99        sample         16.700           ms/op
Client.listUser:listUser·p0.999       sample         26.941           ms/op
Client.listUser:listUser·p0.9999      sample         28.213           ms/op
Client.listUser:listUser·p1.00        sample         28.213           ms/op
