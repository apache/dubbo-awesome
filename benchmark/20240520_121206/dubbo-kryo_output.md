# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.741 ops/ms
Iteration   1: 7.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.553 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.362 ops/ms
Iteration   1: 12.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.625 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.306 ops/ms
Iteration   1: 12.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.484 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.158 ops/ms
Iteration   1: 8.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.044 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ±(99.9%) 0.074 ms/op
Iteration   1: 2.234 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.234 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.493 ±(99.9%) 0.094 ms/op
Iteration   1: 1.764 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.764 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.507 ±(99.9%) 0.059 ms/op
Iteration   1: 1.960 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.960 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.337 ±(99.9%) 0.084 ms/op
Iteration   1: 3.399 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.399 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.614 ±(99.9%) 0.088 ms/op
Iteration   1: 2.218 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.523 ms/op
                 createUser·p0.50:   2.011 ms/op
                 createUser·p0.90:   2.671 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   10.645 ms/op
                 createUser·p0.999:  16.588 ms/op
                 createUser·p0.9999: 18.223 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14412
  mean =      2.218 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 195 
    [ 1.250,  2.500) = 11963 
    [ 2.500,  3.750) = 1929 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =     10.645 ms/op
     p(99.9000) =     16.588 ms/op
     p(99.9900) =     18.223 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.927 ±(99.9%) 0.069 ms/op
Iteration   1: 1.763 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.351 ms/op
                 existUser·p0.50:   1.645 ms/op
                 existUser·p0.90:   2.122 ms/op
                 existUser·p0.95:   2.310 ms/op
                 existUser·p0.99:   3.857 ms/op
                 existUser·p0.999:  15.448 ms/op
                 existUser·p0.9999: 16.010 ms/op
                 existUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18123
  mean =      1.763 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 696 
    [ 1.250,  2.500) = 16853 
    [ 2.500,  3.750) = 376 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.351 ms/op
     p(50.0000) =      1.645 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.310 ms/op
     p(99.0000) =      3.857 ms/op
     p(99.9000) =     15.448 ms/op
     p(99.9900) =     16.010 ms/op
     p(99.9990) =     16.024 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.202 ±(99.9%) 0.078 ms/op
Iteration   1: 1.936 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.608 ms/op
                 getUser·p0.50:   1.860 ms/op
                 getUser·p0.90:   2.441 ms/op
                 getUser·p0.95:   2.609 ms/op
                 getUser·p0.99:   3.152 ms/op
                 getUser·p0.999:  12.747 ms/op
                 getUser·p0.9999: 13.216 ms/op
                 getUser·p1.00:   13.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16648
  mean =      1.936 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 287 
    [ 1.250,  2.500) = 15140 
    [ 2.500,  3.750) = 1093 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.152 ms/op
     p(99.9000) =     12.747 ms/op
     p(99.9900) =     13.216 ms/op
     p(99.9990) =     13.238 ms/op
     p(99.9999) =     13.238 ms/op
    p(100.0000) =     13.238 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.782 ±(99.9%) 0.206 ms/op
Iteration   1: 3.139 ±(99.9%) 0.049 ms/op
                 listUser·p0.00:   0.907 ms/op
                 listUser·p0.50:   2.781 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  22.315 ms/op
                 listUser·p0.9999: 22.708 ms/op
                 listUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10180
  mean =      3.139 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1922 
    [ 2.500,  5.000) = 8051 
    [ 5.000,  7.500) = 143 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      2.781 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     22.315 ms/op
     p(99.9900) =     22.708 ms/op
     p(99.9990) =     22.708 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.553          ops/ms
ClientSimple.existUser                       thrpt         12.625          ops/ms
ClientSimple.getUser                         thrpt         12.484          ops/ms
ClientSimple.listUser                        thrpt          8.044          ops/ms
ClientSimple.createUser                       avgt          2.234           ms/op
ClientSimple.existUser                        avgt          1.764           ms/op
ClientSimple.getUser                          avgt          1.960           ms/op
ClientSimple.listUser                         avgt          3.399           ms/op
ClientSimple.createUser                     sample  14412   2.218 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.523           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.011           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.645           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.588           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.223           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.743           ms/op
ClientSimple.existUser                      sample  18123   1.763 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.351           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.645           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.122           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.310           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.857           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.448           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.010           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.024           ms/op
ClientSimple.getUser                        sample  16648   1.936 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.608           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.860           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.441           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.152           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.747           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.216           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.238           ms/op
ClientSimple.listUser                       sample  10180   3.139 ± 0.049   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.907           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.781           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.014           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.710           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.315           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.708           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.708           ms/op

Benchmark result is saved to 1716206865318.json
