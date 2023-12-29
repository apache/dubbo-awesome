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
# Warmup Iteration   1: 2.198 ops/ms
Iteration   1: 6.476 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.476 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.867 ops/ms
Iteration   1: 12.990 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.990 ops/ms


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
# Warmup Iteration   1: 3.911 ops/ms
Iteration   1: 8.599 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.599 ops/ms


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
# Warmup Iteration   1: 2.227 ops/ms
Iteration   1: 3.612 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.612 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.727 ±(99.9%) 0.083 ms/op
Iteration   1: 3.362 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.362 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.662 ±(99.9%) 0.037 ms/op
Iteration   1: 2.078 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.078 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.790 ±(99.9%) 0.051 ms/op
Iteration   1: 3.194 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.194 ms/op


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
# Warmup Iteration   1: 14.029 ±(99.9%) 0.320 ms/op
Iteration   1: 8.272 ±(99.9%) 0.077 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.272 ms/op


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
# Warmup Iteration   1: 5.346 ±(99.9%) 0.139 ms/op
Iteration   1: 3.036 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.875 ms/op
                 createUser·p0.90:   4.032 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.339 ms/op
                 createUser·p0.999:  9.781 ms/op
                 createUser·p0.9999: 9.847 ms/op
                 createUser·p1.00:   9.847 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10505
  mean =      3.036 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 18 
    [ 1.500,  2.000) = 84 
    [ 2.000,  2.500) = 2195 
    [ 2.500,  3.000) = 3882 
    [ 3.000,  3.500) = 2585 
    [ 3.500,  4.000) = 671 
    [ 4.000,  4.500) = 675 
    [ 4.500,  5.000) = 200 
    [ 5.000,  5.500) = 50 
    [ 5.500,  6.000) = 22 
    [ 6.000,  6.500) = 27 
    [ 6.500,  7.000) = 25 
    [ 7.000,  7.500) = 4 
    [ 7.500,  8.000) = 3 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 25 
    [ 9.000,  9.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      4.032 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.339 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =      9.847 ms/op
     p(99.9990) =      9.847 ms/op
     p(99.9999) =      9.847 ms/op
    p(100.0000) =      9.847 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.262 ±(99.9%) 0.074 ms/op
Iteration   1: 1.902 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   1.761 ms/op
                 existUser·p0.90:   2.585 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  18.648 ms/op
                 existUser·p0.9999: 18.849 ms/op
                 existUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16907
  mean =      1.902 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1026 
    [ 1.250,  2.500) = 13764 
    [ 2.500,  3.750) = 1899 
    [ 3.750,  5.000) = 138 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =     18.648 ms/op
     p(99.9900) =     18.849 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.448 ±(99.9%) 0.102 ms/op
Iteration   1: 2.923 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   2.814 ms/op
                 getUser·p0.90:   3.710 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   5.281 ms/op
                 getUser·p0.999:  7.619 ms/op
                 getUser·p0.9999: 8.820 ms/op
                 getUser·p1.00:   8.946 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11042
  mean =      2.923 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 23 
    [1.500, 2.000) = 191 
    [2.000, 2.500) = 3010 
    [2.500, 3.000) = 3525 
    [3.000, 3.500) = 2491 
    [3.500, 4.000) = 1240 
    [4.000, 4.500) = 319 
    [4.500, 5.000) = 112 
    [5.000, 5.500) = 42 
    [5.500, 6.000) = 31 
    [6.000, 6.500) = 26 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 5 
    [7.500, 8.000) = 21 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.710 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.281 ms/op
     p(99.9000) =      7.619 ms/op
     p(99.9900) =      8.820 ms/op
     p(99.9990) =      8.946 ms/op
     p(99.9999) =      8.946 ms/op
    p(100.0000) =      8.946 ms/op


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
# Warmup Iteration   1: 11.873 ±(99.9%) 0.422 ms/op
Iteration   1: 9.083 ±(99.9%) 0.151 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   8.806 ms/op
                 listUser·p0.90:   12.222 ms/op
                 listUser·p0.95:   13.697 ms/op
                 listUser·p0.99:   20.997 ms/op
                 listUser·p0.999:  23.822 ms/op
                 listUser·p0.9999: 25.264 ms/op
                 listUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3526
  mean =      9.083 ±(99.9%) 0.151 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 116 
    [ 5.000,  7.500) = 864 
    [ 7.500, 10.000) = 1577 
    [10.000, 12.500) = 656 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.380 ms/op
     p(50.0000) =      8.806 ms/op
     p(90.0000) =     12.222 ms/op
     p(95.0000) =     13.697 ms/op
     p(99.0000) =     20.997 ms/op
     p(99.9000) =     23.822 ms/op
     p(99.9900) =     25.264 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.476          ops/ms
Client.existUser                       thrpt         12.990          ops/ms
Client.getUser                         thrpt          8.599          ops/ms
Client.listUser                        thrpt          3.612          ops/ms
Client.createUser                       avgt          3.362           ms/op
Client.existUser                        avgt          2.078           ms/op
Client.getUser                          avgt          3.194           ms/op
Client.listUser                         avgt          8.272           ms/op
Client.createUser                     sample  10505   3.036 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          1.063           ms/op
Client.createUser:createUser·p0.50    sample          2.875           ms/op
Client.createUser:createUser·p0.90    sample          4.032           ms/op
Client.createUser:createUser·p0.95    sample          4.358           ms/op
Client.createUser:createUser·p0.99    sample          6.339           ms/op
Client.createUser:createUser·p0.999   sample          9.781           ms/op
Client.createUser:createUser·p0.9999  sample          9.847           ms/op
Client.createUser:createUser·p1.00    sample          9.847           ms/op
Client.existUser                      sample  16907   1.902 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.679           ms/op
Client.existUser:existUser·p0.50      sample          1.761           ms/op
Client.existUser:existUser·p0.90      sample          2.585           ms/op
Client.existUser:existUser·p0.95      sample          2.789           ms/op
Client.existUser:existUser·p0.99      sample          3.936           ms/op
Client.existUser:existUser·p0.999     sample         18.648           ms/op
Client.existUser:existUser·p0.9999    sample         18.849           ms/op
Client.existUser:existUser·p1.00      sample         18.940           ms/op
Client.getUser                        sample  11042   2.923 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          1.145           ms/op
Client.getUser:getUser·p0.50          sample          2.814           ms/op
Client.getUser:getUser·p0.90          sample          3.710           ms/op
Client.getUser:getUser·p0.95          sample          4.014           ms/op
Client.getUser:getUser·p0.99          sample          5.281           ms/op
Client.getUser:getUser·p0.999         sample          7.619           ms/op
Client.getUser:getUser·p0.9999        sample          8.820           ms/op
Client.getUser:getUser·p1.00          sample          8.946           ms/op
Client.listUser                       sample   3526   9.083 ± 0.151   ms/op
Client.listUser:listUser·p0.00        sample          2.380           ms/op
Client.listUser:listUser·p0.50        sample          8.806           ms/op
Client.listUser:listUser·p0.90        sample         12.222           ms/op
Client.listUser:listUser·p0.95        sample         13.697           ms/op
Client.listUser:listUser·p0.99        sample         20.997           ms/op
Client.listUser:listUser·p0.999       sample         23.822           ms/op
Client.listUser:listUser·p0.9999      sample         25.264           ms/op
Client.listUser:listUser·p1.00        sample         25.264           ms/op
