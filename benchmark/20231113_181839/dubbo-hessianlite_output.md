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
# Warmup Iteration   1: 2.079 ops/ms
Iteration   1: 5.757 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.757 ops/ms


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
# Warmup Iteration   1: 6.419 ops/ms
Iteration   1: 12.885 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.885 ops/ms


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
# Warmup Iteration   1: 3.988 ops/ms
Iteration   1: 9.259 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.259 ops/ms


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
# Warmup Iteration   1: 2.359 ops/ms
Iteration   1: 3.408 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.408 ops/ms


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
# Warmup Iteration   1: 5.707 ±(99.9%) 0.112 ms/op
Iteration   1: 2.791 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.791 ms/op


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
# Warmup Iteration   1: 2.983 ±(99.9%) 0.031 ms/op
Iteration   1: 1.921 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.921 ms/op


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
# Warmup Iteration   1: 4.877 ±(99.9%) 0.056 ms/op
Iteration   1: 3.016 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.016 ms/op


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
# Warmup Iteration   1: 13.227 ±(99.9%) 0.379 ms/op
Iteration   1: 9.008 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.008 ms/op


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
# Warmup Iteration   1: 4.709 ±(99.9%) 0.100 ms/op
Iteration   1: 2.948 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   2.769 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   6.042 ms/op
                 createUser·p0.999:  16.274 ms/op
                 createUser·p0.9999: 17.331 ms/op
                 createUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10845
  mean =      2.948 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 3007 
    [ 2.500,  3.750) = 6912 
    [ 3.750,  5.000) = 751 
    [ 5.000,  6.250) = 73 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      2.769 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      6.042 ms/op
     p(99.9000) =     16.274 ms/op
     p(99.9900) =     17.331 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 2.933 ±(99.9%) 0.052 ms/op
Iteration   1: 1.861 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.600 ms/op
                 existUser·p0.50:   1.663 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   3.351 ms/op
                 existUser·p0.999:  20.414 ms/op
                 existUser·p0.9999: 20.513 ms/op
                 existUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17175
  mean =      1.861 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16000 
    [ 2.500,  5.000) = 1100 
    [ 5.000,  7.500) = 11 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      1.663 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.351 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 4.778 ±(99.9%) 0.128 ms/op
Iteration   1: 2.952 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   2.896 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.087 ms/op
                 getUser·p0.99:   5.185 ms/op
                 getUser·p0.999:  18.678 ms/op
                 getUser·p0.9999: 19.530 ms/op
                 getUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11001
  mean =      2.952 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 3120 
    [ 2.500,  3.750) = 6144 
    [ 3.750,  5.000) = 1457 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.087 ms/op
     p(99.0000) =      5.185 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     19.530 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 11.377 ±(99.9%) 0.395 ms/op
Iteration   1: 8.484 ±(99.9%) 0.114 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   8.184 ms/op
                 listUser·p0.90:   11.256 ms/op
                 listUser·p0.95:   12.435 ms/op
                 listUser·p0.99:   14.749 ms/op
                 listUser·p0.999:  18.098 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3779
  mean =      8.484 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 7 
    [ 2.500,  3.750) = 7 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 848 
    [ 7.500,  8.750) = 957 
    [ 8.750, 10.000) = 737 
    [10.000, 11.250) = 397 
    [11.250, 12.500) = 196 
    [12.500, 13.750) = 130 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      8.184 ms/op
     p(90.0000) =     11.256 ms/op
     p(95.0000) =     12.435 ms/op
     p(99.0000) =     14.749 ms/op
     p(99.9000) =     18.098 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.757          ops/ms
Client.existUser                       thrpt         12.885          ops/ms
Client.getUser                         thrpt          9.259          ops/ms
Client.listUser                        thrpt          3.408          ops/ms
Client.createUser                       avgt          2.791           ms/op
Client.existUser                        avgt          1.921           ms/op
Client.getUser                          avgt          3.016           ms/op
Client.listUser                         avgt          9.008           ms/op
Client.createUser                     sample  10845   2.948 ± 0.032   ms/op
Client.createUser:createUser·p0.00    sample          1.120           ms/op
Client.createUser:createUser·p0.50    sample          2.769           ms/op
Client.createUser:createUser·p0.90    sample          3.699           ms/op
Client.createUser:createUser·p0.95    sample          3.916           ms/op
Client.createUser:createUser·p0.99    sample          6.042           ms/op
Client.createUser:createUser·p0.999   sample         16.274           ms/op
Client.createUser:createUser·p0.9999  sample         17.331           ms/op
Client.createUser:createUser·p1.00    sample         17.334           ms/op
Client.existUser                      sample  17175   1.861 ± 0.025   ms/op
Client.existUser:existUser·p0.00      sample          0.600           ms/op
Client.existUser:existUser·p0.50      sample          1.663           ms/op
Client.existUser:existUser·p0.90      sample          2.376           ms/op
Client.existUser:existUser·p0.95      sample          2.601           ms/op
Client.existUser:existUser·p0.99      sample          3.351           ms/op
Client.existUser:existUser·p0.999     sample         20.414           ms/op
Client.existUser:existUser·p0.9999    sample         20.513           ms/op
Client.existUser:existUser·p1.00      sample         20.513           ms/op
Client.getUser                        sample  11001   2.952 ± 0.036   ms/op
Client.getUser:getUser·p0.00          sample          0.720           ms/op
Client.getUser:getUser·p0.50          sample          2.896           ms/op
Client.getUser:getUser·p0.90          sample          3.883           ms/op
Client.getUser:getUser·p0.95          sample          4.087           ms/op
Client.getUser:getUser·p0.99          sample          5.185           ms/op
Client.getUser:getUser·p0.999         sample         18.678           ms/op
Client.getUser:getUser·p0.9999        sample         19.530           ms/op
Client.getUser:getUser·p1.00          sample         19.530           ms/op
Client.listUser                       sample   3779   8.484 ± 0.114   ms/op
Client.listUser:listUser·p0.00        sample          1.571           ms/op
Client.listUser:listUser·p0.50        sample          8.184           ms/op
Client.listUser:listUser·p0.90        sample         11.256           ms/op
Client.listUser:listUser·p0.95        sample         12.435           ms/op
Client.listUser:listUser·p0.99        sample         14.749           ms/op
Client.listUser:listUser·p0.999       sample         18.098           ms/op
Client.listUser:listUser·p0.9999      sample         19.628           ms/op
Client.listUser:listUser·p1.00        sample         19.628           ms/op
