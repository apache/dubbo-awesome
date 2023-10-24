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
# Warmup Iteration   1: 1.654 ops/ms
Iteration   1: 4.604 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.604 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.745 ops/ms
Iteration   1: 10.907 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.907 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.272 ops/ms
Iteration   1: 7.166 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.166 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.179 ops/ms
Iteration   1: 2.019 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.019 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 10.277 ±(99.9%) 0.201 ms/op
Iteration   1: 5.704 ±(99.9%) 0.084 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.704 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.068 ±(99.9%) 0.104 ms/op
Iteration   1: 2.940 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.940 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.782 ±(99.9%) 0.109 ms/op
Iteration   1: 3.362 ±(99.9%) 0.073 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 23.191 ±(99.9%) 0.497 ms/op
Iteration   1: 16.247 ±(99.9%) 0.310 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.247 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.865 ±(99.9%) 0.282 ms/op
Iteration   1: 3.483 ±(99.9%) 0.073 ms/op
                 createUser·p0.00:   1.720 ms/op
                 createUser·p0.50:   2.777 ms/op
                 createUser·p0.90:   5.194 ms/op
                 createUser·p0.95:   6.472 ms/op
                 createUser·p0.99:   13.795 ms/op
                 createUser·p0.999:  24.216 ms/op
                 createUser·p0.9999: 25.919 ms/op
                 createUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9399
  mean =      3.483 ±(99.9%) 0.073 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 961 
    [ 2.500,  5.000) = 7388 
    [ 5.000,  7.500) = 681 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      2.777 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      6.472 ms/op
     p(99.0000) =     13.795 ms/op
     p(99.9000) =     24.216 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.149 ms/op
Iteration   1: 1.756 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.564 ms/op
                 existUser·p0.50:   1.567 ms/op
                 existUser·p0.90:   2.054 ms/op
                 existUser·p0.95:   2.978 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 13.940 ms/op
                 existUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18198
  mean =      1.756 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1635 
    [ 1.250,  2.500) = 15327 
    [ 2.500,  3.750) = 640 
    [ 3.750,  5.000) = 262 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 78 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      1.567 ms/op
     p(90.0000) =      2.054 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     13.940 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 8.217 ±(99.9%) 0.217 ms/op
Iteration   1: 3.151 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   2.785 ms/op
                 getUser·p0.90:   4.020 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   9.257 ms/op
                 getUser·p0.999:  16.192 ms/op
                 getUser·p0.9999: 16.765 ms/op
                 getUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10355
  mean =      3.151 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1858 
    [ 2.500,  3.750) = 7197 
    [ 3.750,  5.000) = 606 
    [ 5.000,  6.250) = 378 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      4.020 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     16.192 ms/op
     p(99.9900) =     16.765 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 21.221 ±(99.9%) 0.813 ms/op
Iteration   1: 12.663 ±(99.9%) 0.242 ms/op
                 listUser·p0.00:   4.981 ms/op
                 listUser·p0.50:   11.796 ms/op
                 listUser·p0.90:   17.859 ms/op
                 listUser·p0.95:   20.129 ms/op
                 listUser·p0.99:   23.752 ms/op
                 listUser·p0.999:  28.668 ms/op
                 listUser·p0.9999: 29.131 ms/op
                 listUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2513
  mean =     12.663 ±(99.9%) 0.242 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 2 
    [ 5.000,  7.500) = 102 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 928 
    [12.500, 15.000) = 524 
    [15.000, 17.500) = 267 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      4.981 ms/op
     p(50.0000) =     11.796 ms/op
     p(90.0000) =     17.859 ms/op
     p(95.0000) =     20.129 ms/op
     p(99.0000) =     23.752 ms/op
     p(99.9000) =     28.668 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.604          ops/ms
Client.existUser                       thrpt         10.907          ops/ms
Client.getUser                         thrpt          7.166          ops/ms
Client.listUser                        thrpt          2.019          ops/ms
Client.createUser                       avgt          5.704           ms/op
Client.existUser                        avgt          2.940           ms/op
Client.getUser                          avgt          3.362           ms/op
Client.listUser                         avgt         16.247           ms/op
Client.createUser                     sample   9399   3.483 ± 0.073   ms/op
Client.createUser:createUser·p0.00    sample          1.720           ms/op
Client.createUser:createUser·p0.50    sample          2.777           ms/op
Client.createUser:createUser·p0.90    sample          5.194           ms/op
Client.createUser:createUser·p0.95    sample          6.472           ms/op
Client.createUser:createUser·p0.99    sample         13.795           ms/op
Client.createUser:createUser·p0.999   sample         24.216           ms/op
Client.createUser:createUser·p0.9999  sample         25.919           ms/op
Client.createUser:createUser·p1.00    sample         25.919           ms/op
Client.existUser                      sample  18198   1.756 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.564           ms/op
Client.existUser:existUser·p0.50      sample          1.567           ms/op
Client.existUser:existUser·p0.90      sample          2.054           ms/op
Client.existUser:existUser·p0.95      sample          2.978           ms/op
Client.existUser:existUser·p0.99      sample          6.398           ms/op
Client.existUser:existUser·p0.999     sample         13.058           ms/op
Client.existUser:existUser·p0.9999    sample         13.940           ms/op
Client.existUser:existUser·p1.00      sample         14.451           ms/op
Client.getUser                        sample  10355   3.151 ± 0.046   ms/op
Client.getUser:getUser·p0.00          sample          0.682           ms/op
Client.getUser:getUser·p0.50          sample          2.785           ms/op
Client.getUser:getUser·p0.90          sample          4.020           ms/op
Client.getUser:getUser·p0.95          sample          5.521           ms/op
Client.getUser:getUser·p0.99          sample          9.257           ms/op
Client.getUser:getUser·p0.999         sample         16.192           ms/op
Client.getUser:getUser·p0.9999        sample         16.765           ms/op
Client.getUser:getUser·p1.00          sample         16.777           ms/op
Client.listUser                       sample   2513  12.663 ± 0.242   ms/op
Client.listUser:listUser·p0.00        sample          4.981           ms/op
Client.listUser:listUser·p0.50        sample         11.796           ms/op
Client.listUser:listUser·p0.90        sample         17.859           ms/op
Client.listUser:listUser·p0.95        sample         20.129           ms/op
Client.listUser:listUser·p0.99        sample         23.752           ms/op
Client.listUser:listUser·p0.999       sample         28.668           ms/op
Client.listUser:listUser·p0.9999      sample         29.131           ms/op
Client.listUser:listUser·p1.00        sample         29.131           ms/op
