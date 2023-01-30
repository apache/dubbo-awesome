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
# Warmup Iteration   1: 1.014 ops/ms
Iteration   1: 2.447 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.447 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.147 ops/ms
Iteration   1: 9.476 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.476 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.145 ops/ms
Iteration   1: 5.139 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.139 ops/ms


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
# Warmup Iteration   1: 0.878 ops/ms
Iteration   1: 1.403 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.403 ops/ms


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
# Warmup Iteration   1: 12.849 ±(99.9%) 0.206 ms/op
Iteration   1: 6.185 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.185 ms/op


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
# Warmup Iteration   1: 5.521 ±(99.9%) 0.062 ms/op
Iteration   1: 3.757 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.757 ms/op


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
# Warmup Iteration   1: 8.745 ±(99.9%) 0.133 ms/op
Iteration   1: 4.808 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.808 ms/op


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
# Warmup Iteration   1: 27.120 ±(99.9%) 0.526 ms/op
Iteration   1: 16.147 ±(99.9%) 0.106 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.147 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.827 ±(99.9%) 0.283 ms/op
Iteration   1: 5.582 ±(99.9%) 0.080 ms/op
                 createUser·p0.00:   2.990 ms/op
                 createUser·p0.50:   5.407 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.029 ms/op
                 createUser·p0.99:   17.251 ms/op
                 createUser·p0.999:  27.435 ms/op
                 createUser·p0.9999: 27.492 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5876
  mean =      5.582 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 813 
    [ 5.000,  7.500) = 4927 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      2.990 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      5.849 ms/op
     p(95.0000) =      6.029 ms/op
     p(99.0000) =     17.251 ms/op
     p(99.9000) =     27.435 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 5.983 ±(99.9%) 0.163 ms/op
Iteration   1: 4.029 ±(99.9%) 0.061 ms/op
                 existUser·p0.00:   0.921 ms/op
                 existUser·p0.50:   3.932 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   5.110 ms/op
                 existUser·p0.99:   12.468 ms/op
                 existUser·p0.999:  18.285 ms/op
                 existUser·p0.9999: 19.300 ms/op
                 existUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7944
  mean =      4.029 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 601 
    [ 2.500,  3.750) = 1200 
    [ 3.750,  5.000) = 5716 
    [ 5.000,  6.250) = 96 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      5.110 ms/op
     p(99.0000) =     12.468 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 10.611 ±(99.9%) 0.323 ms/op
Iteration   1: 4.360 ±(99.9%) 0.081 ms/op
                 getUser·p0.00:   1.624 ms/op
                 getUser·p0.50:   4.129 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   6.111 ms/op
                 getUser·p0.99:   16.416 ms/op
                 getUser·p0.999:  27.312 ms/op
                 getUser·p0.9999: 29.426 ms/op
                 getUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7500
  mean =      4.360 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 6246 
    [ 5.000,  7.500) = 1039 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      6.111 ms/op
     p(99.0000) =     16.416 ms/op
     p(99.9000) =     27.312 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     29.426 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


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
# Warmup Iteration   1: 24.314 ±(99.9%) 0.781 ms/op
Iteration   1: 15.750 ±(99.9%) 0.189 ms/op
                 listUser·p0.00:   5.358 ms/op
                 listUser·p0.50:   15.712 ms/op
                 listUser·p0.90:   17.990 ms/op
                 listUser·p0.95:   19.464 ms/op
                 listUser·p0.99:   24.923 ms/op
                 listUser·p0.999:  28.397 ms/op
                 listUser·p0.9999: 30.867 ms/op
                 listUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2034
  mean =     15.750 ±(99.9%) 0.189 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 600 
    [15.000, 17.500) = 931 
    [17.500, 20.000) = 274 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      5.358 ms/op
     p(50.0000) =     15.712 ms/op
     p(90.0000) =     17.990 ms/op
     p(95.0000) =     19.464 ms/op
     p(99.0000) =     24.923 ms/op
     p(99.9000) =     28.397 ms/op
     p(99.9900) =     30.867 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.447          ops/ms
Client.existUser                       thrpt         9.476          ops/ms
Client.getUser                         thrpt         5.139          ops/ms
Client.listUser                        thrpt         1.403          ops/ms
Client.createUser                       avgt         6.185           ms/op
Client.existUser                        avgt         3.757           ms/op
Client.getUser                          avgt         4.808           ms/op
Client.listUser                         avgt        16.147           ms/op
Client.createUser                     sample  5876   5.582 ± 0.080   ms/op
Client.createUser:createUser·p0.00    sample         2.990           ms/op
Client.createUser:createUser·p0.50    sample         5.407           ms/op
Client.createUser:createUser·p0.90    sample         5.849           ms/op
Client.createUser:createUser·p0.95    sample         6.029           ms/op
Client.createUser:createUser·p0.99    sample        17.251           ms/op
Client.createUser:createUser·p0.999   sample        27.435           ms/op
Client.createUser:createUser·p0.9999  sample        27.492           ms/op
Client.createUser:createUser·p1.00    sample        27.492           ms/op
Client.existUser                      sample  7944   4.029 ± 0.061   ms/op
Client.existUser:existUser·p0.00      sample         0.921           ms/op
Client.existUser:existUser·p0.50      sample         3.932           ms/op
Client.existUser:existUser·p0.90      sample         4.252           ms/op
Client.existUser:existUser·p0.95      sample         5.110           ms/op
Client.existUser:existUser·p0.99      sample        12.468           ms/op
Client.existUser:existUser·p0.999     sample        18.285           ms/op
Client.existUser:existUser·p0.9999    sample        19.300           ms/op
Client.existUser:existUser·p1.00      sample        19.300           ms/op
Client.getUser                        sample  7500   4.360 ± 0.081   ms/op
Client.getUser:getUser·p0.00          sample         1.624           ms/op
Client.getUser:getUser·p0.50          sample         4.129           ms/op
Client.getUser:getUser·p0.90          sample         5.399           ms/op
Client.getUser:getUser·p0.95          sample         6.111           ms/op
Client.getUser:getUser·p0.99          sample        16.416           ms/op
Client.getUser:getUser·p0.999         sample        27.312           ms/op
Client.getUser:getUser·p0.9999        sample        29.426           ms/op
Client.getUser:getUser·p1.00          sample        29.426           ms/op
Client.listUser                       sample  2034  15.750 ± 0.189   ms/op
Client.listUser:listUser·p0.00        sample         5.358           ms/op
Client.listUser:listUser·p0.50        sample        15.712           ms/op
Client.listUser:listUser·p0.90        sample        17.990           ms/op
Client.listUser:listUser·p0.95        sample        19.464           ms/op
Client.listUser:listUser·p0.99        sample        24.923           ms/op
Client.listUser:listUser·p0.999       sample        28.397           ms/op
Client.listUser:listUser·p0.9999      sample        30.867           ms/op
Client.listUser:listUser·p1.00        sample        30.867           ms/op
