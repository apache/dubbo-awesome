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
# Warmup Iteration   1: 1.105 ops/ms
Iteration   1: 2.164 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.164 ops/ms


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
# Warmup Iteration   1: 2.680 ops/ms
Iteration   1: 5.796 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.796 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.805 ops/ms
Iteration   1: 4.777 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.777 ops/ms


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
# Warmup Iteration   1: 0.918 ops/ms
Iteration   1: 1.346 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.346 ops/ms


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
# Warmup Iteration   1: 19.540 ±(99.9%) 0.271 ms/op
Iteration   1: 9.064 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.064 ms/op


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
# Warmup Iteration   1: 7.712 ±(99.9%) 0.094 ms/op
Iteration   1: 4.055 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.055 ms/op


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
# Warmup Iteration   1: 9.683 ±(99.9%) 0.126 ms/op
Iteration   1: 4.613 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.613 ms/op


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
# Warmup Iteration   1: 27.590 ±(99.9%) 0.413 ms/op
Iteration   1: 19.214 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  19.214 ms/op


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
# Warmup Iteration   1: 13.310 ±(99.9%) 0.363 ms/op
Iteration   1: 7.204 ±(99.9%) 0.152 ms/op
                 createUser·p0.00:   3.219 ms/op
                 createUser·p0.50:   6.758 ms/op
                 createUser·p0.90:   7.578 ms/op
                 createUser·p0.95:   8.880 ms/op
                 createUser·p0.99:   24.052 ms/op
                 createUser·p0.999:  28.527 ms/op
                 createUser·p0.9999: 28.803 ms/op
                 createUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4432
  mean =      7.204 ±(99.9%) 0.152 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 252 
    [ 5.000,  7.500) = 3616 
    [ 7.500, 10.000) = 370 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      3.219 ms/op
     p(50.0000) =      6.758 ms/op
     p(90.0000) =      7.578 ms/op
     p(95.0000) =      8.880 ms/op
     p(99.0000) =     24.052 ms/op
     p(99.9000) =     28.527 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 8.152 ±(99.9%) 0.240 ms/op
Iteration   1: 3.770 ±(99.9%) 0.061 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   7.053 ms/op
                 existUser·p0.99:   12.435 ms/op
                 existUser·p0.999:  13.976 ms/op
                 existUser·p0.9999: 14.270 ms/op
                 existUser·p1.00:   14.270 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8479
  mean =      3.770 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 742 
    [ 2.500,  3.750) = 4901 
    [ 3.750,  5.000) = 2167 
    [ 5.000,  6.250) = 177 
    [ 6.250,  7.500) = 135 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      7.053 ms/op
     p(99.0000) =     12.435 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     14.270 ms/op
     p(99.9990) =     14.270 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 11.157 ±(99.9%) 0.433 ms/op
Iteration   1: 4.540 ±(99.9%) 0.052 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   4.370 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.644 ms/op
                 getUser·p0.99:   7.889 ms/op
                 getUser·p0.999:  22.278 ms/op
                 getUser·p0.9999: 22.839 ms/op
                 getUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7130
  mean =      4.540 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 5870 
    [ 5.000,  7.500) = 1164 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      4.370 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     22.278 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     22.839 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 26.040 ±(99.9%) 0.771 ms/op
Iteration   1: 18.066 ±(99.9%) 0.235 ms/op
                 listUser·p0.00:   4.497 ms/op
                 listUser·p0.50:   17.105 ms/op
                 listUser·p0.90:   20.149 ms/op
                 listUser·p0.95:   24.932 ms/op
                 listUser·p0.99:   30.474 ms/op
                 listUser·p0.999:  31.433 ms/op
                 listUser·p0.9999: 32.047 ms/op
                 listUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1780
  mean =     18.066 ±(99.9%) 0.235 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4 
    [ 5.000,  7.500) = 2 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 1175 
    [17.500, 20.000) = 401 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      4.497 ms/op
     p(50.0000) =     17.105 ms/op
     p(90.0000) =     20.149 ms/op
     p(95.0000) =     24.932 ms/op
     p(99.0000) =     30.474 ms/op
     p(99.9000) =     31.433 ms/op
     p(99.9900) =     32.047 ms/op
     p(99.9990) =     32.047 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.164          ops/ms
Client.existUser                       thrpt         5.796          ops/ms
Client.getUser                         thrpt         4.777          ops/ms
Client.listUser                        thrpt         1.346          ops/ms
Client.createUser                       avgt         9.064           ms/op
Client.existUser                        avgt         4.055           ms/op
Client.getUser                          avgt         4.613           ms/op
Client.listUser                         avgt        19.214           ms/op
Client.createUser                     sample  4432   7.204 ± 0.152   ms/op
Client.createUser:createUser·p0.00    sample         3.219           ms/op
Client.createUser:createUser·p0.50    sample         6.758           ms/op
Client.createUser:createUser·p0.90    sample         7.578           ms/op
Client.createUser:createUser·p0.95    sample         8.880           ms/op
Client.createUser:createUser·p0.99    sample        24.052           ms/op
Client.createUser:createUser·p0.999   sample        28.527           ms/op
Client.createUser:createUser·p0.9999  sample        28.803           ms/op
Client.createUser:createUser·p1.00    sample        28.803           ms/op
Client.existUser                      sample  8479   3.770 ± 0.061   ms/op
Client.existUser:existUser·p0.00      sample         1.010           ms/op
Client.existUser:existUser·p0.50      sample         3.359           ms/op
Client.existUser:existUser·p0.90      sample         4.440           ms/op
Client.existUser:existUser·p0.95      sample         7.053           ms/op
Client.existUser:existUser·p0.99      sample        12.435           ms/op
Client.existUser:existUser·p0.999     sample        13.976           ms/op
Client.existUser:existUser·p0.9999    sample        14.270           ms/op
Client.existUser:existUser·p1.00      sample        14.270           ms/op
Client.getUser                        sample  7130   4.540 ± 0.052   ms/op
Client.getUser:getUser·p0.00          sample         1.530           ms/op
Client.getUser:getUser·p0.50          sample         4.370           ms/op
Client.getUser:getUser·p0.90          sample         5.325           ms/op
Client.getUser:getUser·p0.95          sample         5.644           ms/op
Client.getUser:getUser·p0.99          sample         7.889           ms/op
Client.getUser:getUser·p0.999         sample        22.278           ms/op
Client.getUser:getUser·p0.9999        sample        22.839           ms/op
Client.getUser:getUser·p1.00          sample        22.839           ms/op
Client.listUser                       sample  1780  18.066 ± 0.235   ms/op
Client.listUser:listUser·p0.00        sample         4.497           ms/op
Client.listUser:listUser·p0.50        sample        17.105           ms/op
Client.listUser:listUser·p0.90        sample        20.149           ms/op
Client.listUser:listUser·p0.95        sample        24.932           ms/op
Client.listUser:listUser·p0.99        sample        30.474           ms/op
Client.listUser:listUser·p0.999       sample        31.433           ms/op
Client.listUser:listUser·p0.9999      sample        32.047           ms/op
Client.listUser:listUser·p1.00        sample        32.047           ms/op
