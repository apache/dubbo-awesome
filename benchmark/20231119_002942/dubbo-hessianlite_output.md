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
# Warmup Iteration   1: 2.500 ops/ms
Iteration   1: 6.075 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.075 ops/ms


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
# Warmup Iteration   1: 6.683 ops/ms
Iteration   1: 12.917 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.917 ops/ms


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
# Warmup Iteration   1: 4.824 ops/ms
Iteration   1: 10.101 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.101 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.416 ops/ms
Iteration   1: 3.940 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.940 ops/ms


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
# Warmup Iteration   1: 4.520 ±(99.9%) 0.055 ms/op
Iteration   1: 2.748 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.748 ms/op


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
# Warmup Iteration   1: 2.954 ±(99.9%) 0.034 ms/op
Iteration   1: 2.195 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.195 ms/op


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
# Warmup Iteration   1: 4.430 ±(99.9%) 0.061 ms/op
Iteration   1: 3.105 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.105 ms/op


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
# Warmup Iteration   1: 13.268 ±(99.9%) 0.184 ms/op
Iteration   1: 8.000 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.000 ms/op


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.097 ms/op
Iteration   1: 2.980 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   2.851 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  12.422 ms/op
                 createUser·p0.9999: 13.881 ms/op
                 createUser·p1.00:   13.910 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10806
  mean =      2.980 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 15 
    [ 1.250,  2.500) = 2716 
    [ 2.500,  3.750) = 7162 
    [ 3.750,  5.000) = 684 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     12.422 ms/op
     p(99.9900) =     13.881 ms/op
     p(99.9990) =     13.910 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 2.817 ±(99.9%) 0.058 ms/op
Iteration   1: 2.024 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.456 ms/op
                 existUser·p0.50:   1.982 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   4.784 ms/op
                 existUser·p0.999:  12.681 ms/op
                 existUser·p0.9999: 13.055 ms/op
                 existUser·p1.00:   13.074 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15815
  mean =      2.024 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 672 
    [ 1.250,  2.500) = 13834 
    [ 2.500,  3.750) = 1084 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      1.982 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =     12.681 ms/op
     p(99.9900) =     13.055 ms/op
     p(99.9990) =     13.074 ms/op
     p(99.9999) =     13.074 ms/op
    p(100.0000) =     13.074 ms/op


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.080 ms/op
Iteration   1: 2.953 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.931 ms/op
                 getUser·p0.99:   5.054 ms/op
                 getUser·p0.999:  12.866 ms/op
                 getUser·p0.9999: 13.183 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10905
  mean =      2.953 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 3037 
    [ 2.500,  3.750) = 7034 
    [ 3.750,  5.000) = 705 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.931 ms/op
     p(99.0000) =      5.054 ms/op
     p(99.9000) =     12.866 ms/op
     p(99.9900) =     13.183 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 11.707 ±(99.9%) 0.394 ms/op
Iteration   1: 8.297 ±(99.9%) 0.114 ms/op
                 listUser·p0.00:   3.400 ms/op
                 listUser·p0.50:   7.856 ms/op
                 listUser·p0.90:   11.158 ms/op
                 listUser·p0.95:   11.960 ms/op
                 listUser·p0.99:   15.057 ms/op
                 listUser·p0.999:  18.718 ms/op
                 listUser·p0.9999: 19.661 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3887
  mean =      8.297 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 3 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 490 
    [ 6.250,  7.500) = 1093 
    [ 7.500,  8.750) = 850 
    [ 8.750, 10.000) = 555 
    [10.000, 11.250) = 465 
    [11.250, 12.500) = 229 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      3.400 ms/op
     p(50.0000) =      7.856 ms/op
     p(90.0000) =     11.158 ms/op
     p(95.0000) =     11.960 ms/op
     p(99.0000) =     15.057 ms/op
     p(99.9000) =     18.718 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     19.661 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.075          ops/ms
Client.existUser                       thrpt         12.917          ops/ms
Client.getUser                         thrpt         10.101          ops/ms
Client.listUser                        thrpt          3.940          ops/ms
Client.createUser                       avgt          2.748           ms/op
Client.existUser                        avgt          2.195           ms/op
Client.getUser                          avgt          3.105           ms/op
Client.listUser                         avgt          8.000           ms/op
Client.createUser                     sample  10806   2.980 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          0.527           ms/op
Client.createUser:createUser·p0.50    sample          2.851           ms/op
Client.createUser:createUser·p0.90    sample          3.670           ms/op
Client.createUser:createUser·p0.95    sample          4.014           ms/op
Client.createUser:createUser·p0.99    sample          8.004           ms/op
Client.createUser:createUser·p0.999   sample         12.422           ms/op
Client.createUser:createUser·p0.9999  sample         13.881           ms/op
Client.createUser:createUser·p1.00    sample         13.910           ms/op
Client.existUser                      sample  15815   2.024 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.456           ms/op
Client.existUser:existUser·p0.50      sample          1.982           ms/op
Client.existUser:existUser·p0.90      sample          2.470           ms/op
Client.existUser:existUser·p0.95      sample          2.597           ms/op
Client.existUser:existUser·p0.99      sample          4.784           ms/op
Client.existUser:existUser·p0.999     sample         12.681           ms/op
Client.existUser:existUser·p0.9999    sample         13.055           ms/op
Client.existUser:existUser·p1.00      sample         13.074           ms/op
Client.getUser                        sample  10905   2.953 ± 0.029   ms/op
Client.getUser:getUser·p0.00          sample          0.554           ms/op
Client.getUser:getUser·p0.50          sample          2.945           ms/op
Client.getUser:getUser·p0.90          sample          3.662           ms/op
Client.getUser:getUser·p0.95          sample          3.931           ms/op
Client.getUser:getUser·p0.99          sample          5.054           ms/op
Client.getUser:getUser·p0.999         sample         12.866           ms/op
Client.getUser:getUser·p0.9999        sample         13.183           ms/op
Client.getUser:getUser·p1.00          sample         13.189           ms/op
Client.listUser                       sample   3887   8.297 ± 0.114   ms/op
Client.listUser:listUser·p0.00        sample          3.400           ms/op
Client.listUser:listUser·p0.50        sample          7.856           ms/op
Client.listUser:listUser·p0.90        sample         11.158           ms/op
Client.listUser:listUser·p0.95        sample         11.960           ms/op
Client.listUser:listUser·p0.99        sample         15.057           ms/op
Client.listUser:listUser·p0.999       sample         18.718           ms/op
Client.listUser:listUser·p0.9999      sample         19.661           ms/op
Client.listUser:listUser·p1.00        sample         19.661           ms/op
