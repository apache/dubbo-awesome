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
# Warmup Iteration   1: 1.294 ops/ms
Iteration   1: 2.303 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.303 ops/ms


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
# Warmup Iteration   1: 2.403 ops/ms
Iteration   1: 9.053 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.053 ops/ms


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
# Warmup Iteration   1: 2.317 ops/ms
Iteration   1: 6.042 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.042 ops/ms


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
# Warmup Iteration   1: 0.889 ops/ms
Iteration   1: 1.703 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.703 ops/ms


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
# Warmup Iteration   1: 16.241 ±(99.9%) 0.218 ms/op
Iteration   1: 7.401 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.401 ms/op


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
# Warmup Iteration   1: 7.684 ±(99.9%) 0.100 ms/op
Iteration   1: 3.466 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.466 ms/op


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
# Warmup Iteration   1: 8.229 ±(99.9%) 0.164 ms/op
Iteration   1: 4.063 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.063 ms/op


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
# Warmup Iteration   1: 25.332 ±(99.9%) 0.425 ms/op
Iteration   1: 14.823 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  14.823 ms/op


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
# Warmup Iteration   1: 10.136 ±(99.9%) 0.380 ms/op
Iteration   1: 6.287 ±(99.9%) 0.076 ms/op
                 createUser·p0.00:   4.202 ms/op
                 createUser·p0.50:   5.890 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   8.585 ms/op
                 createUser·p0.99:   15.491 ms/op
                 createUser·p0.999:  19.035 ms/op
                 createUser·p0.9999: 19.202 ms/op
                 createUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5083
  mean =      6.287 ±(99.9%) 0.076 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 0 
    [ 3.750,  5.000) = 7 
    [ 5.000,  6.250) = 4066 
    [ 6.250,  7.500) = 679 
    [ 7.500,  8.750) = 90 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      4.202 ms/op
     p(50.0000) =      5.890 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     15.491 ms/op
     p(99.9000) =     19.035 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 6.832 ±(99.9%) 0.177 ms/op
Iteration   1: 3.547 ±(99.9%) 0.069 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   3.908 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.488 ms/op
                 existUser·p0.99:   12.272 ms/op
                 existUser·p0.999:  28.238 ms/op
                 existUser·p0.9999: 29.950 ms/op
                 existUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9123
  mean =      3.547 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2349 
    [ 2.500,  5.000) = 6566 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.488 ms/op
     p(99.0000) =     12.272 ms/op
     p(99.9000) =     28.238 ms/op
     p(99.9900) =     29.950 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 11.813 ±(99.9%) 0.639 ms/op
Iteration   1: 4.189 ±(99.9%) 0.057 ms/op
                 getUser·p0.00:   1.571 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.691 ms/op
                 getUser·p0.99:   12.567 ms/op
                 getUser·p0.999:  18.612 ms/op
                 getUser·p0.9999: 19.202 ms/op
                 getUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7664
  mean =      4.189 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 64 
    [ 2.500,  3.750) = 3373 
    [ 3.750,  5.000) = 3350 
    [ 5.000,  6.250) = 592 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.691 ms/op
     p(99.0000) =     12.567 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 25.932 ±(99.9%) 0.802 ms/op
Iteration   1: 16.940 ±(99.9%) 0.232 ms/op
                 listUser·p0.00:   8.389 ms/op
                 listUser·p0.50:   16.761 ms/op
                 listUser·p0.90:   19.431 ms/op
                 listUser·p0.95:   23.182 ms/op
                 listUser·p0.99:   27.099 ms/op
                 listUser·p0.999:  32.843 ms/op
                 listUser·p0.9999: 33.456 ms/op
                 listUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1890
  mean =     16.940 ±(99.9%) 0.232 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 648 
    [17.500, 20.000) = 723 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      8.389 ms/op
     p(50.0000) =     16.761 ms/op
     p(90.0000) =     19.431 ms/op
     p(95.0000) =     23.182 ms/op
     p(99.0000) =     27.099 ms/op
     p(99.9000) =     32.843 ms/op
     p(99.9900) =     33.456 ms/op
     p(99.9990) =     33.456 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.303          ops/ms
Client.existUser                       thrpt         9.053          ops/ms
Client.getUser                         thrpt         6.042          ops/ms
Client.listUser                        thrpt         1.703          ops/ms
Client.createUser                       avgt         7.401           ms/op
Client.existUser                        avgt         3.466           ms/op
Client.getUser                          avgt         4.063           ms/op
Client.listUser                         avgt        14.823           ms/op
Client.createUser                     sample  5083   6.287 ± 0.076   ms/op
Client.createUser:createUser·p0.00    sample         4.202           ms/op
Client.createUser:createUser·p0.50    sample         5.890           ms/op
Client.createUser:createUser·p0.90    sample         6.693           ms/op
Client.createUser:createUser·p0.95    sample         8.585           ms/op
Client.createUser:createUser·p0.99    sample        15.491           ms/op
Client.createUser:createUser·p0.999   sample        19.035           ms/op
Client.createUser:createUser·p0.9999  sample        19.202           ms/op
Client.createUser:createUser·p1.00    sample        19.202           ms/op
Client.existUser                      sample  9123   3.547 ± 0.069   ms/op
Client.existUser:existUser·p0.00      sample         0.643           ms/op
Client.existUser:existUser·p0.50      sample         3.908           ms/op
Client.existUser:existUser·p0.90      sample         4.293           ms/op
Client.existUser:existUser·p0.95      sample         4.488           ms/op
Client.existUser:existUser·p0.99      sample        12.272           ms/op
Client.existUser:existUser·p0.999     sample        28.238           ms/op
Client.existUser:existUser·p0.9999    sample        29.950           ms/op
Client.existUser:existUser·p1.00      sample        29.950           ms/op
Client.getUser                        sample  7664   4.189 ± 0.057   ms/op
Client.getUser:getUser·p0.00          sample         1.571           ms/op
Client.getUser:getUser·p0.50          sample         3.936           ms/op
Client.getUser:getUser·p0.90          sample         5.095           ms/op
Client.getUser:getUser·p0.95          sample         5.691           ms/op
Client.getUser:getUser·p0.99          sample        12.567           ms/op
Client.getUser:getUser·p0.999         sample        18.612           ms/op
Client.getUser:getUser·p0.9999        sample        19.202           ms/op
Client.getUser:getUser·p1.00          sample        19.202           ms/op
Client.listUser                       sample  1890  16.940 ± 0.232   ms/op
Client.listUser:listUser·p0.00        sample         8.389           ms/op
Client.listUser:listUser·p0.50        sample        16.761           ms/op
Client.listUser:listUser·p0.90        sample        19.431           ms/op
Client.listUser:listUser·p0.95        sample        23.182           ms/op
Client.listUser:listUser·p0.99        sample        27.099           ms/op
Client.listUser:listUser·p0.999       sample        32.843           ms/op
Client.listUser:listUser·p0.9999      sample        33.456           ms/op
Client.listUser:listUser·p1.00        sample        33.456           ms/op
