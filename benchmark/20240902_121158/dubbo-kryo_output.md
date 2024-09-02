# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.983 ops/ms
Iteration   1: 7.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.781 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.544 ops/ms
Iteration   1: 11.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.268 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.550 ops/ms
Iteration   1: 13.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.262 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.267 ops/ms
Iteration   1: 8.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.522 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.400 ±(99.9%) 0.097 ms/op
Iteration   1: 2.401 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.401 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.095 ±(99.9%) 0.055 ms/op
Iteration   1: 1.893 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.893 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.242 ±(99.9%) 0.060 ms/op
Iteration   1: 1.911 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.911 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.347 ±(99.9%) 0.096 ms/op
Iteration   1: 3.781 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.781 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.523 ±(99.9%) 0.086 ms/op
Iteration   1: 2.017 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   1.884 ms/op
                 createUser·p0.90:   2.474 ms/op
                 createUser·p0.95:   2.792 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  15.417 ms/op
                 createUser·p0.9999: 20.424 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15846
  mean =      2.017 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14327 
    [ 2.500,  5.000) = 1348 
    [ 5.000,  7.500) = 79 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.792 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     15.417 ms/op
     p(99.9900) =     20.424 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.887 ±(99.9%) 0.079 ms/op
Iteration   1: 2.014 ±(99.9%) 0.059 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.265 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   5.005 ms/op
                 existUser·p0.999:  51.837 ms/op
                 existUser·p0.9999: 54.591 ms/op
                 existUser·p1.00:   54.591 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16024
  mean =      2.014 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15863 
    [ 5.000, 10.000) = 92 
    [10.000, 15.000) = 35 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 4 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =     51.837 ms/op
     p(99.9900) =     54.591 ms/op
     p(99.9990) =     54.591 ms/op
     p(99.9999) =     54.591 ms/op
    p(100.0000) =     54.591 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.042 ±(99.9%) 0.073 ms/op
Iteration   1: 2.083 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   1.946 ms/op
                 getUser·p0.90:   2.679 ms/op
                 getUser·p0.95:   2.896 ms/op
                 getUser·p0.99:   3.449 ms/op
                 getUser·p0.999:  5.633 ms/op
                 getUser·p0.9999: 8.842 ms/op
                 getUser·p1.00:   9.044 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15365
  mean =      2.083 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 2 
    [ 1.000,  2.000) = 8331 
    [ 2.000,  3.000) = 6533 
    [ 3.000,  4.000) = 403 
    [ 4.000,  5.000) = 39 
    [ 5.000,  6.000) = 46 
    [ 6.000,  7.000) = 7 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =      3.449 ms/op
     p(99.9000) =      5.633 ms/op
     p(99.9900) =      8.842 ms/op
     p(99.9990) =      9.044 ms/op
     p(99.9999) =      9.044 ms/op
    p(100.0000) =      9.044 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.549 ±(99.9%) 0.143 ms/op
Iteration   1: 3.389 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.400 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  7.435 ms/op
                 listUser·p0.9999: 7.520 ms/op
                 listUser·p1.00:   7.520 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9435
  mean =      3.389 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 22 
    [1.500, 2.000) = 78 
    [2.000, 2.500) = 789 
    [2.500, 3.000) = 1449 
    [3.000, 3.500) = 3164 
    [3.500, 4.000) = 2931 
    [4.000, 4.500) = 571 
    [4.500, 5.000) = 177 
    [5.000, 5.500) = 73 
    [5.500, 6.000) = 104 
    [6.000, 6.500) = 42 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =      7.435 ms/op
     p(99.9900) =      7.520 ms/op
     p(99.9990) =      7.520 ms/op
     p(99.9999) =      7.520 ms/op
    p(100.0000) =      7.520 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.781          ops/ms
ClientSimple.existUser                       thrpt         11.268          ops/ms
ClientSimple.getUser                         thrpt         13.262          ops/ms
ClientSimple.listUser                        thrpt          8.522          ops/ms
ClientSimple.createUser                       avgt          2.401           ms/op
ClientSimple.existUser                        avgt          1.893           ms/op
ClientSimple.getUser                          avgt          1.911           ms/op
ClientSimple.listUser                         avgt          3.781           ms/op
ClientSimple.createUser                     sample  15846   2.017 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.729           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.884           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.474           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.792           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.620           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.417           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.424           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.037           ms/op
ClientSimple.existUser                      sample  16024   2.014 ± 0.059   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.648           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.804           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.265           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.005           ms/op
ClientSimple.existUser:existUser·p0.999     sample         51.837           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         54.591           ms/op
ClientSimple.existUser:existUser·p1.00      sample         54.591           ms/op
ClientSimple.getUser                        sample  15365   2.083 ± 0.013   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.962           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.946           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.896           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.449           ms/op
ClientSimple.getUser:getUser·p0.999         sample          5.633           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          8.842           ms/op
ClientSimple.getUser:getUser·p1.00          sample          9.044           ms/op
ClientSimple.listUser                       sample   9435   3.389 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.124           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.400           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.022           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.808           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.435           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.520           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.520           ms/op

Benchmark result is saved to 1725278844835.json
