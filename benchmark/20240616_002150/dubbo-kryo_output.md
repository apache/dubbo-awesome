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
# Warmup Iteration   1: 1.801 ops/ms
Iteration   1: 7.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.568 ops/ms


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
# Warmup Iteration   1: 6.416 ops/ms
Iteration   1: 11.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.922 ops/ms


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
# Warmup Iteration   1: 6.043 ops/ms
Iteration   1: 15.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.411 ops/ms


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
# Warmup Iteration   1: 4.613 ops/ms
Iteration   1: 8.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.615 ops/ms


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.066 ms/op
Iteration   1: 2.184 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.184 ms/op


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
# Warmup Iteration   1: 3.152 ±(99.9%) 0.047 ms/op
Iteration   1: 1.978 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.978 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ±(99.9%) 0.059 ms/op
Iteration   1: 2.190 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.190 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.422 ±(99.9%) 0.153 ms/op
Iteration   1: 3.661 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.661 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.557 ±(99.9%) 0.121 ms/op
Iteration   1: 2.085 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   1.880 ms/op
                 createUser·p0.90:   2.638 ms/op
                 createUser·p0.95:   2.859 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  36.176 ms/op
                 createUser·p0.9999: 38.168 ms/op
                 createUser·p1.00:   38.273 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15318
  mean =      2.085 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13127 
    [ 2.500,  5.000) = 2095 
    [ 5.000,  7.500) = 19 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =     36.176 ms/op
     p(99.9900) =     38.168 ms/op
     p(99.9990) =     38.273 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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
# Warmup Iteration   1: 2.916 ±(99.9%) 0.067 ms/op
Iteration   1: 1.895 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.466 ms/op
                 existUser·p0.99:   3.593 ms/op
                 existUser·p0.999:  17.863 ms/op
                 existUser·p0.9999: 18.426 ms/op
                 existUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16878
  mean =      1.895 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 992 
    [ 1.250,  2.500) = 15146 
    [ 2.500,  3.750) = 587 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.593 ms/op
     p(99.9000) =     17.863 ms/op
     p(99.9900) =     18.426 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.306 ±(99.9%) 0.093 ms/op
Iteration   1: 2.011 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.478 ms/op
                 getUser·p0.50:   1.833 ms/op
                 getUser·p0.90:   2.707 ms/op
                 getUser·p0.95:   2.974 ms/op
                 getUser·p0.99:   4.639 ms/op
                 getUser·p0.999:  17.826 ms/op
                 getUser·p0.9999: 18.101 ms/op
                 getUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15973
  mean =      2.011 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 422 
    [ 1.250,  2.500) = 13123 
    [ 2.500,  3.750) = 2201 
    [ 3.750,  5.000) = 99 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.974 ms/op
     p(99.0000) =      4.639 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     18.101 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 4.420 ±(99.9%) 0.124 ms/op
Iteration   1: 3.709 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   0.642 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   10.357 ms/op
                 listUser·p0.999:  23.200 ms/op
                 listUser·p0.9999: 25.133 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8617
  mean =      3.709 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 270 
    [ 2.500,  5.000) = 7878 
    [ 5.000,  7.500) = 315 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =     10.357 ms/op
     p(99.9000) =     23.200 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     25.133 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.568          ops/ms
ClientSimple.existUser                       thrpt         11.922          ops/ms
ClientSimple.getUser                         thrpt         15.411          ops/ms
ClientSimple.listUser                        thrpt          8.615          ops/ms
ClientSimple.createUser                       avgt          2.184           ms/op
ClientSimple.existUser                        avgt          1.978           ms/op
ClientSimple.getUser                          avgt          2.190           ms/op
ClientSimple.listUser                         avgt          3.661           ms/op
ClientSimple.createUser                     sample  15318   2.085 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.776           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.880           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.859           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.965           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.176           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.168           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.273           ms/op
ClientSimple.existUser                      sample  16878   1.895 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.632           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.810           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.593           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.863           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.426           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.448           ms/op
ClientSimple.getUser                        sample  15973   2.011 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.478           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.833           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.974           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.639           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.826           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.101           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.121           ms/op
ClientSimple.listUser                       sample   8617   3.709 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.642           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.576           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.120           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.357           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.200           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.133           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.133           ms/op

Benchmark result is saved to 1718497060213.json
