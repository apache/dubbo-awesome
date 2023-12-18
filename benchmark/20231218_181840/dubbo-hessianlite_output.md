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
# Warmup Iteration   1: 2.248 ops/ms
Iteration   1: 5.651 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.651 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.618 ops/ms
Iteration   1: 14.083 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.083 ops/ms


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
# Warmup Iteration   1: 3.767 ops/ms
Iteration   1: 8.157 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.157 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.243 ops/ms
Iteration   1: 3.862 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.862 ops/ms


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
# Warmup Iteration   1: 5.272 ±(99.9%) 0.064 ms/op
Iteration   1: 3.050 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.050 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.039 ms/op
Iteration   1: 1.984 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.984 ms/op


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
# Warmup Iteration   1: 4.533 ±(99.9%) 0.048 ms/op
Iteration   1: 3.441 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.441 ms/op


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
# Warmup Iteration   1: 12.713 ±(99.9%) 0.234 ms/op
Iteration   1: 8.351 ±(99.9%) 0.123 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.351 ms/op


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
# Warmup Iteration   1: 5.035 ±(99.9%) 0.115 ms/op
Iteration   1: 2.974 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   2.699 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.526 ms/op
                 createUser·p0.999:  29.983 ms/op
                 createUser·p0.9999: 31.276 ms/op
                 createUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10740
  mean =      2.974 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3338 
    [ 2.500,  5.000) = 7242 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      2.699 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.526 ms/op
     p(99.9000) =     29.983 ms/op
     p(99.9900) =     31.276 ms/op
     p(99.9990) =     31.293 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 3.179 ±(99.9%) 0.066 ms/op
Iteration   1: 1.630 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.430 ms/op
                 existUser·p0.50:   1.540 ms/op
                 existUser·p0.90:   2.048 ms/op
                 existUser·p0.95:   2.318 ms/op
                 existUser·p0.99:   2.707 ms/op
                 existUser·p0.999:  8.343 ms/op
                 existUser·p0.9999: 8.455 ms/op
                 existUser·p1.00:   8.471 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19614
  mean =      1.630 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 3 
    [0.500, 1.000) = 152 
    [1.000, 1.500) = 8137 
    [1.500, 2.000) = 9053 
    [2.000, 2.500) = 1793 
    [2.500, 3.000) = 365 
    [3.000, 3.500) = 33 
    [3.500, 4.000) = 8 
    [4.000, 4.500) = 5 
    [4.500, 5.000) = 28 
    [5.000, 5.500) = 2 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 3 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.430 ms/op
     p(50.0000) =      1.540 ms/op
     p(90.0000) =      2.048 ms/op
     p(95.0000) =      2.318 ms/op
     p(99.0000) =      2.707 ms/op
     p(99.9000) =      8.343 ms/op
     p(99.9900) =      8.455 ms/op
     p(99.9990) =      8.471 ms/op
     p(99.9999) =      8.471 ms/op
    p(100.0000) =      8.471 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.085 ms/op
Iteration   1: 3.188 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.279 ms/op
                 getUser·p0.999:  16.564 ms/op
                 getUser·p0.9999: 16.810 ms/op
                 getUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10023
  mean =      3.188 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1935 
    [ 2.500,  3.750) = 6565 
    [ 3.750,  5.000) = 1322 
    [ 5.000,  6.250) = 99 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.279 ms/op
     p(99.9000) =     16.564 ms/op
     p(99.9900) =     16.810 ms/op
     p(99.9990) =     16.810 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 13.959 ±(99.9%) 0.441 ms/op
Iteration   1: 8.748 ±(99.9%) 0.154 ms/op
                 listUser·p0.00:   2.912 ms/op
                 listUser·p0.50:   8.200 ms/op
                 listUser·p0.90:   11.829 ms/op
                 listUser·p0.95:   13.435 ms/op
                 listUser·p0.99:   19.512 ms/op
                 listUser·p0.999:  26.896 ms/op
                 listUser·p0.9999: 29.852 ms/op
                 listUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3650
  mean =      8.748 ±(99.9%) 0.154 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 127 
    [ 5.000,  7.500) = 1126 
    [ 7.500, 10.000) = 1563 
    [10.000, 12.500) = 564 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.912 ms/op
     p(50.0000) =      8.200 ms/op
     p(90.0000) =     11.829 ms/op
     p(95.0000) =     13.435 ms/op
     p(99.0000) =     19.512 ms/op
     p(99.9000) =     26.896 ms/op
     p(99.9900) =     29.852 ms/op
     p(99.9990) =     29.852 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.651          ops/ms
Client.existUser                       thrpt         14.083          ops/ms
Client.getUser                         thrpt          8.157          ops/ms
Client.listUser                        thrpt          3.862          ops/ms
Client.createUser                       avgt          3.050           ms/op
Client.existUser                        avgt          1.984           ms/op
Client.getUser                          avgt          3.441           ms/op
Client.listUser                         avgt          8.351           ms/op
Client.createUser                     sample  10740   2.974 ± 0.052   ms/op
Client.createUser:createUser·p0.00    sample          1.081           ms/op
Client.createUser:createUser·p0.50    sample          2.699           ms/op
Client.createUser:createUser·p0.90    sample          3.998           ms/op
Client.createUser:createUser·p0.95    sample          4.284           ms/op
Client.createUser:createUser·p0.99    sample          5.526           ms/op
Client.createUser:createUser·p0.999   sample         29.983           ms/op
Client.createUser:createUser·p0.9999  sample         31.276           ms/op
Client.createUser:createUser·p1.00    sample         31.293           ms/op
Client.existUser                      sample  19614   1.630 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.430           ms/op
Client.existUser:existUser·p0.50      sample          1.540           ms/op
Client.existUser:existUser·p0.90      sample          2.048           ms/op
Client.existUser:existUser·p0.95      sample          2.318           ms/op
Client.existUser:existUser·p0.99      sample          2.707           ms/op
Client.existUser:existUser·p0.999     sample          8.343           ms/op
Client.existUser:existUser·p0.9999    sample          8.455           ms/op
Client.existUser:existUser·p1.00      sample          8.471           ms/op
Client.getUser                        sample  10023   3.188 ± 0.041   ms/op
Client.getUser:getUser·p0.00          sample          1.192           ms/op
Client.getUser:getUser·p0.50          sample          3.043           ms/op
Client.getUser:getUser·p0.90          sample          3.908           ms/op
Client.getUser:getUser·p0.95          sample          4.301           ms/op
Client.getUser:getUser·p0.99          sample          6.279           ms/op
Client.getUser:getUser·p0.999         sample         16.564           ms/op
Client.getUser:getUser·p0.9999        sample         16.810           ms/op
Client.getUser:getUser·p1.00          sample         16.810           ms/op
Client.listUser                       sample   3650   8.748 ± 0.154   ms/op
Client.listUser:listUser·p0.00        sample          2.912           ms/op
Client.listUser:listUser·p0.50        sample          8.200           ms/op
Client.listUser:listUser·p0.90        sample         11.829           ms/op
Client.listUser:listUser·p0.95        sample         13.435           ms/op
Client.listUser:listUser·p0.99        sample         19.512           ms/op
Client.listUser:listUser·p0.999       sample         26.896           ms/op
Client.listUser:listUser·p0.9999      sample         29.852           ms/op
Client.listUser:listUser·p1.00        sample         29.852           ms/op
