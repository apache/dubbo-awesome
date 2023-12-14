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
# Warmup Iteration   1: 2.147 ops/ms
Iteration   1: 5.480 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.480 ops/ms


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
# Warmup Iteration   1: 6.550 ops/ms
Iteration   1: 13.464 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.464 ops/ms


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
# Warmup Iteration   1: 3.840 ops/ms
Iteration   1: 8.338 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.338 ops/ms


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
# Warmup Iteration   1: 2.008 ops/ms
Iteration   1: 3.723 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.723 ops/ms


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
# Warmup Iteration   1: 5.424 ±(99.9%) 0.072 ms/op
Iteration   1: 3.182 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.182 ms/op


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
# Warmup Iteration   1: 3.611 ±(99.9%) 0.034 ms/op
Iteration   1: 1.835 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.835 ms/op


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
# Warmup Iteration   1: 4.785 ±(99.9%) 0.041 ms/op
Iteration   1: 2.726 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.726 ms/op


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
# Warmup Iteration   1: 11.631 ±(99.9%) 0.261 ms/op
Iteration   1: 7.567 ±(99.9%) 0.052 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.567 ms/op


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
# Warmup Iteration   1: 4.457 ±(99.9%) 0.098 ms/op
Iteration   1: 2.932 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   2.748 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.226 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  9.798 ms/op
                 createUser·p0.9999: 9.845 ms/op
                 createUser·p1.00:   9.847 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10902
  mean =      2.932 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 3 
    [ 1.000,  2.000) = 314 
    [ 2.000,  3.000) = 6966 
    [ 3.000,  4.000) = 2903 
    [ 4.000,  5.000) = 427 
    [ 5.000,  6.000) = 131 
    [ 6.000,  7.000) = 59 
    [ 7.000,  8.000) = 32 
    [ 8.000,  9.000) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.748 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.226 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =      9.845 ms/op
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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.307 ±(99.9%) 0.080 ms/op
Iteration   1: 2.082 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.030 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  17.039 ms/op
                 existUser·p0.9999: 17.153 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15363
  mean =      2.082 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 717 
    [ 1.250,  2.500) = 12627 
    [ 2.500,  3.750) = 1903 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     17.153 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.101 ms/op
Iteration   1: 3.047 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.248 ms/op
                 getUser·p0.99:   5.606 ms/op
                 getUser·p0.999:  10.584 ms/op
                 getUser·p0.9999: 10.697 ms/op
                 getUser·p1.00:   10.699 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10488
  mean =      3.047 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 2726 
    [ 2.500,  3.750) = 6377 
    [ 3.750,  5.000) = 1213 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.248 ms/op
     p(99.0000) =      5.606 ms/op
     p(99.9000) =     10.584 ms/op
     p(99.9900) =     10.697 ms/op
     p(99.9990) =     10.699 ms/op
     p(99.9999) =     10.699 ms/op
    p(100.0000) =     10.699 ms/op


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
# Warmup Iteration   1: 11.309 ±(99.9%) 0.349 ms/op
Iteration   1: 7.806 ±(99.9%) 0.139 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   7.283 ms/op
                 listUser·p0.90:   10.420 ms/op
                 listUser·p0.95:   11.551 ms/op
                 listUser·p0.99:   19.857 ms/op
                 listUser·p0.999:  28.666 ms/op
                 listUser·p0.9999: 31.588 ms/op
                 listUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4094
  mean =      7.806 ±(99.9%) 0.139 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 256 
    [ 5.000,  7.500) = 1956 
    [ 7.500, 10.000) = 1327 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.507 ms/op
     p(50.0000) =      7.283 ms/op
     p(90.0000) =     10.420 ms/op
     p(95.0000) =     11.551 ms/op
     p(99.0000) =     19.857 ms/op
     p(99.9000) =     28.666 ms/op
     p(99.9900) =     31.588 ms/op
     p(99.9990) =     31.588 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.480          ops/ms
Client.existUser                       thrpt         13.464          ops/ms
Client.getUser                         thrpt          8.338          ops/ms
Client.listUser                        thrpt          3.723          ops/ms
Client.createUser                       avgt          3.182           ms/op
Client.existUser                        avgt          1.835           ms/op
Client.getUser                          avgt          2.726           ms/op
Client.listUser                         avgt          7.567           ms/op
Client.createUser                     sample  10902   2.932 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          0.914           ms/op
Client.createUser:createUser·p0.50    sample          2.748           ms/op
Client.createUser:createUser·p0.90    sample          3.736           ms/op
Client.createUser:createUser·p0.95    sample          4.226           ms/op
Client.createUser:createUser·p0.99    sample          6.570           ms/op
Client.createUser:createUser·p0.999   sample          9.798           ms/op
Client.createUser:createUser·p0.9999  sample          9.845           ms/op
Client.createUser:createUser·p1.00    sample          9.847           ms/op
Client.existUser                      sample  15363   2.082 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.546           ms/op
Client.existUser:existUser·p0.50      sample          2.030           ms/op
Client.existUser:existUser·p0.90      sample          2.601           ms/op
Client.existUser:existUser·p0.95      sample          2.802           ms/op
Client.existUser:existUser·p0.99      sample          3.641           ms/op
Client.existUser:existUser·p0.999     sample         17.039           ms/op
Client.existUser:existUser·p0.9999    sample         17.153           ms/op
Client.existUser:existUser·p1.00      sample         17.170           ms/op
Client.getUser                        sample  10488   3.047 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.643           ms/op
Client.getUser:getUser·p0.50          sample          2.986           ms/op
Client.getUser:getUser·p0.90          sample          3.887           ms/op
Client.getUser:getUser·p0.95          sample          4.248           ms/op
Client.getUser:getUser·p0.99          sample          5.606           ms/op
Client.getUser:getUser·p0.999         sample         10.584           ms/op
Client.getUser:getUser·p0.9999        sample         10.697           ms/op
Client.getUser:getUser·p1.00          sample         10.699           ms/op
Client.listUser                       sample   4094   7.806 ± 0.139   ms/op
Client.listUser:listUser·p0.00        sample          2.507           ms/op
Client.listUser:listUser·p0.50        sample          7.283           ms/op
Client.listUser:listUser·p0.90        sample         10.420           ms/op
Client.listUser:listUser·p0.95        sample         11.551           ms/op
Client.listUser:listUser·p0.99        sample         19.857           ms/op
Client.listUser:listUser·p0.999       sample         28.666           ms/op
Client.listUser:listUser·p0.9999      sample         31.588           ms/op
Client.listUser:listUser·p1.00        sample         31.588           ms/op
