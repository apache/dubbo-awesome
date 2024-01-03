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
# Warmup Iteration   1: 2.639 ops/ms
Iteration   1: 5.869 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.869 ops/ms


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
# Warmup Iteration   1: 5.537 ops/ms
Iteration   1: 12.153 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.153 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.186 ops/ms
Iteration   1: 9.156 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.156 ops/ms


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
# Warmup Iteration   1: 2.147 ops/ms
Iteration   1: 3.730 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.730 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.641 ±(99.9%) 0.081 ms/op
Iteration   1: 2.975 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.975 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.631 ±(99.9%) 0.040 ms/op
Iteration   1: 1.741 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.741 ms/op


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
# Warmup Iteration   1: 5.003 ±(99.9%) 0.059 ms/op
Iteration   1: 3.563 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.563 ms/op


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
# Warmup Iteration   1: 12.057 ±(99.9%) 0.144 ms/op
Iteration   1: 8.668 ±(99.9%) 0.136 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.668 ms/op


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
# Warmup Iteration   1: 4.909 ±(99.9%) 0.102 ms/op
Iteration   1: 2.917 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.724 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  13.222 ms/op
                 createUser·p0.9999: 15.432 ms/op
                 createUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10996
  mean =      2.917 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 27 
    [ 1.250,  2.500) = 2757 
    [ 2.500,  3.750) = 7017 
    [ 3.750,  5.000) = 1041 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.724 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     13.222 ms/op
     p(99.9900) =     15.432 ms/op
     p(99.9990) =     15.450 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 3.032 ±(99.9%) 0.075 ms/op
Iteration   1: 1.984 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   1.898 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.613 ms/op
                 existUser·p0.99:   3.513 ms/op
                 existUser·p0.999:  27.689 ms/op
                 existUser·p0.9999: 28.699 ms/op
                 existUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16111
  mean =      1.984 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14798 
    [ 2.500,  5.000) = 1243 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      3.513 ms/op
     p(99.9000) =     27.689 ms/op
     p(99.9900) =     28.699 ms/op
     p(99.9990) =     29.000 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.106 ms/op
Iteration   1: 3.482 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   7.006 ms/op
                 getUser·p0.999:  9.355 ms/op
                 getUser·p0.9999: 11.796 ms/op
                 getUser·p1.00:   11.796 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9279
  mean =      3.482 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 911 
    [ 2.500,  3.750) = 5260 
    [ 3.750,  5.000) = 2786 
    [ 5.000,  6.250) = 180 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.006 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.796 ms/op
     p(99.9990) =     11.796 ms/op
     p(99.9999) =     11.796 ms/op
    p(100.0000) =     11.796 ms/op


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
# Warmup Iteration   1: 13.063 ±(99.9%) 0.640 ms/op
Iteration   1: 9.510 ±(99.9%) 0.179 ms/op
                 listUser·p0.00:   3.228 ms/op
                 listUser·p0.50:   8.749 ms/op
                 listUser·p0.90:   13.517 ms/op
                 listUser·p0.95:   15.557 ms/op
                 listUser·p0.99:   20.824 ms/op
                 listUser·p0.999:  27.445 ms/op
                 listUser·p0.9999: 32.276 ms/op
                 listUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3369
  mean =      9.510 ±(99.9%) 0.179 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 48 
    [ 5.000,  7.500) = 842 
    [ 7.500, 10.000) = 1413 
    [10.000, 12.500) = 604 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.228 ms/op
     p(50.0000) =      8.749 ms/op
     p(90.0000) =     13.517 ms/op
     p(95.0000) =     15.557 ms/op
     p(99.0000) =     20.824 ms/op
     p(99.9000) =     27.445 ms/op
     p(99.9900) =     32.276 ms/op
     p(99.9990) =     32.276 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.869          ops/ms
Client.existUser                       thrpt         12.153          ops/ms
Client.getUser                         thrpt          9.156          ops/ms
Client.listUser                        thrpt          3.730          ops/ms
Client.createUser                       avgt          2.975           ms/op
Client.existUser                        avgt          1.741           ms/op
Client.getUser                          avgt          3.563           ms/op
Client.listUser                         avgt          8.668           ms/op
Client.createUser                     sample  10996   2.917 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          0.903           ms/op
Client.createUser:createUser·p0.50    sample          2.724           ms/op
Client.createUser:createUser·p0.90    sample          3.912           ms/op
Client.createUser:createUser·p0.95    sample          4.334           ms/op
Client.createUser:createUser·p0.99    sample          5.235           ms/op
Client.createUser:createUser·p0.999   sample         13.222           ms/op
Client.createUser:createUser·p0.9999  sample         15.432           ms/op
Client.createUser:createUser·p1.00    sample         15.450           ms/op
Client.existUser                      sample  16111   1.984 ± 0.032   ms/op
Client.existUser:existUser·p0.00      sample          0.523           ms/op
Client.existUser:existUser·p0.50      sample          1.898           ms/op
Client.existUser:existUser·p0.90      sample          2.433           ms/op
Client.existUser:existUser·p0.95      sample          2.613           ms/op
Client.existUser:existUser·p0.99      sample          3.513           ms/op
Client.existUser:existUser·p0.999     sample         27.689           ms/op
Client.existUser:existUser·p0.9999    sample         28.699           ms/op
Client.existUser:existUser·p1.00      sample         29.000           ms/op
Client.getUser                        sample   9279   3.482 ± 0.030   ms/op
Client.getUser:getUser·p0.00          sample          0.871           ms/op
Client.getUser:getUser·p0.50          sample          3.445           ms/op
Client.getUser:getUser·p0.90          sample          4.383           ms/op
Client.getUser:getUser·p0.95          sample          4.768           ms/op
Client.getUser:getUser·p0.99          sample          7.006           ms/op
Client.getUser:getUser·p0.999         sample          9.355           ms/op
Client.getUser:getUser·p0.9999        sample         11.796           ms/op
Client.getUser:getUser·p1.00          sample         11.796           ms/op
Client.listUser                       sample   3369   9.510 ± 0.179   ms/op
Client.listUser:listUser·p0.00        sample          3.228           ms/op
Client.listUser:listUser·p0.50        sample          8.749           ms/op
Client.listUser:listUser·p0.90        sample         13.517           ms/op
Client.listUser:listUser·p0.95        sample         15.557           ms/op
Client.listUser:listUser·p0.99        sample         20.824           ms/op
Client.listUser:listUser·p0.999       sample         27.445           ms/op
Client.listUser:listUser·p0.9999      sample         32.276           ms/op
Client.listUser:listUser·p1.00        sample         32.276           ms/op
