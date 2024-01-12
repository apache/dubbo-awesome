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
# Warmup Iteration   1: 2.114 ops/ms
Iteration   1: 5.985 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.985 ops/ms


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
# Warmup Iteration   1: 6.974 ops/ms
Iteration   1: 13.186 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.186 ops/ms


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
# Warmup Iteration   1: 4.347 ops/ms
Iteration   1: 9.170 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.170 ops/ms


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
# Warmup Iteration   1: 2.077 ops/ms
Iteration   1: 3.255 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.255 ops/ms


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
# Warmup Iteration   1: 6.100 ±(99.9%) 0.081 ms/op
Iteration   1: 3.173 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.173 ms/op


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
# Warmup Iteration   1: 3.103 ±(99.9%) 0.043 ms/op
Iteration   1: 1.867 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.867 ms/op


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
# Warmup Iteration   1: 4.778 ±(99.9%) 0.044 ms/op
Iteration   1: 3.118 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.118 ms/op


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
# Warmup Iteration   1: 14.397 ±(99.9%) 0.248 ms/op
Iteration   1: 8.237 ±(99.9%) 0.127 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.237 ms/op


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
# Warmup Iteration   1: 4.972 ±(99.9%) 0.107 ms/op
Iteration   1: 3.271 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   4.323 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  11.784 ms/op
                 createUser·p0.9999: 13.402 ms/op
                 createUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9782
  mean =      3.271 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1244 
    [ 2.500,  3.750) = 6198 
    [ 3.750,  5.000) = 1958 
    [ 5.000,  6.250) = 217 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      4.323 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     11.784 ms/op
     p(99.9900) =     13.402 ms/op
     p(99.9990) =     13.402 ms/op
     p(99.9999) =     13.402 ms/op
    p(100.0000) =     13.402 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.090 ms/op
Iteration   1: 2.048 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.001 ms/op
                 existUser·p0.90:   2.531 ms/op
                 existUser·p0.95:   2.728 ms/op
                 existUser·p0.99:   3.170 ms/op
                 existUser·p0.999:  5.271 ms/op
                 existUser·p0.9999: 6.951 ms/op
                 existUser·p1.00:   7.897 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15605
  mean =      2.048 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 25 
    [1.000, 1.500) = 875 
    [1.500, 2.000) = 6901 
    [2.000, 2.500) = 6048 
    [2.500, 3.000) = 1469 
    [3.000, 3.500) = 175 
    [3.500, 4.000) = 47 
    [4.000, 4.500) = 6 
    [4.500, 5.000) = 38 
    [5.000, 5.500) = 11 
    [5.500, 6.000) = 4 
    [6.000, 6.500) = 5 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      3.170 ms/op
     p(99.9000) =      5.271 ms/op
     p(99.9900) =      6.951 ms/op
     p(99.9990) =      7.897 ms/op
     p(99.9999) =      7.897 ms/op
    p(100.0000) =      7.897 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.094 ms/op
Iteration   1: 3.288 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  21.480 ms/op
                 getUser·p0.9999: 23.691 ms/op
                 getUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9738
  mean =      3.288 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1535 
    [ 2.500,  5.000) = 8012 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     21.480 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 13.466 ±(99.9%) 0.502 ms/op
Iteration   1: 9.731 ±(99.9%) 0.275 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   8.962 ms/op
                 listUser·p0.90:   13.763 ms/op
                 listUser·p0.95:   15.368 ms/op
                 listUser·p0.99:   32.953 ms/op
                 listUser·p0.999:  65.492 ms/op
                 listUser·p0.9999: 78.119 ms/op
                 listUser·p1.00:   78.119 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3281
  mean =      9.731 ±(99.9%) 0.275 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 196 
    [ 5.000, 10.000) = 1914 
    [10.000, 15.000) = 985 
    [15.000, 20.000) = 135 
    [20.000, 25.000) = 14 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 9 
    [40.000, 45.000) = 17 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 1 
    [65.000, 70.000) = 1 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.191 ms/op
     p(50.0000) =      8.962 ms/op
     p(90.0000) =     13.763 ms/op
     p(95.0000) =     15.368 ms/op
     p(99.0000) =     32.953 ms/op
     p(99.9000) =     65.492 ms/op
     p(99.9900) =     78.119 ms/op
     p(99.9990) =     78.119 ms/op
     p(99.9999) =     78.119 ms/op
    p(100.0000) =     78.119 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.985          ops/ms
Client.existUser                       thrpt         13.186          ops/ms
Client.getUser                         thrpt          9.170          ops/ms
Client.listUser                        thrpt          3.255          ops/ms
Client.createUser                       avgt          3.173           ms/op
Client.existUser                        avgt          1.867           ms/op
Client.getUser                          avgt          3.118           ms/op
Client.listUser                         avgt          8.237           ms/op
Client.createUser                     sample   9782   3.271 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          0.820           ms/op
Client.createUser:createUser·p0.50    sample          2.974           ms/op
Client.createUser:createUser·p0.90    sample          4.323           ms/op
Client.createUser:createUser·p0.95    sample          4.784           ms/op
Client.createUser:createUser·p0.99    sample          7.520           ms/op
Client.createUser:createUser·p0.999   sample         11.784           ms/op
Client.createUser:createUser·p0.9999  sample         13.402           ms/op
Client.createUser:createUser·p1.00    sample         13.402           ms/op
Client.existUser                      sample  15605   2.048 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.764           ms/op
Client.existUser:existUser·p0.50      sample          2.001           ms/op
Client.existUser:existUser·p0.90      sample          2.531           ms/op
Client.existUser:existUser·p0.95      sample          2.728           ms/op
Client.existUser:existUser·p0.99      sample          3.170           ms/op
Client.existUser:existUser·p0.999     sample          5.271           ms/op
Client.existUser:existUser·p0.9999    sample          6.951           ms/op
Client.existUser:existUser·p1.00      sample          7.897           ms/op
Client.getUser                        sample   9738   3.288 ± 0.044   ms/op
Client.getUser:getUser·p0.00          sample          0.911           ms/op
Client.getUser:getUser·p0.50          sample          3.207           ms/op
Client.getUser:getUser·p0.90          sample          4.055           ms/op
Client.getUser:getUser·p0.95          sample          4.325           ms/op
Client.getUser:getUser·p0.99          sample          6.160           ms/op
Client.getUser:getUser·p0.999         sample         21.480           ms/op
Client.getUser:getUser·p0.9999        sample         23.691           ms/op
Client.getUser:getUser·p1.00          sample         23.691           ms/op
Client.listUser                       sample   3281   9.731 ± 0.275   ms/op
Client.listUser:listUser·p0.00        sample          2.191           ms/op
Client.listUser:listUser·p0.50        sample          8.962           ms/op
Client.listUser:listUser·p0.90        sample         13.763           ms/op
Client.listUser:listUser·p0.95        sample         15.368           ms/op
Client.listUser:listUser·p0.99        sample         32.953           ms/op
Client.listUser:listUser·p0.999       sample         65.492           ms/op
Client.listUser:listUser·p0.9999      sample         78.119           ms/op
Client.listUser:listUser·p1.00        sample         78.119           ms/op
