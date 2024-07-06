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
# Warmup Iteration   1: 0.937 ops/ms
Iteration   1: 5.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.608 ops/ms


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
# Warmup Iteration   1: 6.308 ops/ms
Iteration   1: 12.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.412 ops/ms


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
# Warmup Iteration   1: 6.236 ops/ms
Iteration   1: 14.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.330 ops/ms


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
# Warmup Iteration   1: 6.043 ops/ms
Iteration   1: 8.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.595 ops/ms


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
# Warmup Iteration   1: 3.727 ±(99.9%) 0.064 ms/op
Iteration   1: 1.999 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.999 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.055 ms/op
Iteration   1: 1.918 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.918 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.061 ms/op
Iteration   1: 1.957 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.957 ms/op


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
# Warmup Iteration   1: 4.412 ±(99.9%) 0.095 ms/op
Iteration   1: 3.101 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.101 ms/op


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
# Warmup Iteration   1: 3.359 ±(99.9%) 0.089 ms/op
Iteration   1: 1.833 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.423 ms/op
                 createUser·p0.50:   1.651 ms/op
                 createUser·p0.90:   2.167 ms/op
                 createUser·p0.95:   2.376 ms/op
                 createUser·p0.99:   5.993 ms/op
                 createUser·p0.999:  28.908 ms/op
                 createUser·p0.9999: 31.876 ms/op
                 createUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 17446
  mean =      1.833 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16720 
    [ 2.500,  5.000) = 509 
    [ 5.000,  7.500) = 89 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      1.651 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.376 ms/op
     p(99.0000) =      5.993 ms/op
     p(99.9000) =     28.908 ms/op
     p(99.9900) =     31.876 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


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
# Warmup Iteration   1: 2.860 ±(99.9%) 0.067 ms/op
Iteration   1: 2.006 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.608 ms/op
                 existUser·p0.50:   1.905 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.781 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  22.861 ms/op
                 existUser·p0.9999: 23.117 ms/op
                 existUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16333
  mean =      2.006 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14550 
    [ 2.500,  5.000) = 1644 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =     22.861 ms/op
     p(99.9900) =     23.117 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 3.318 ±(99.9%) 0.080 ms/op
Iteration   1: 1.929 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   1.761 ms/op
                 getUser·p0.90:   2.462 ms/op
                 getUser·p0.95:   2.687 ms/op
                 getUser·p0.99:   3.518 ms/op
                 getUser·p0.999:  22.577 ms/op
                 getUser·p0.9999: 23.234 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16616
  mean =      1.929 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15095 
    [ 2.500,  5.000) = 1481 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.462 ms/op
     p(95.0000) =      2.687 ms/op
     p(99.0000) =      3.518 ms/op
     p(99.9000) =     22.577 ms/op
     p(99.9900) =     23.234 ms/op
     p(99.9990) =     23.495 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.113 ms/op
Iteration   1: 3.227 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   3.219 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.351 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  20.578 ms/op
                 listUser·p0.9999: 21.823 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9897
  mean =      3.227 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2523 
    [ 2.500,  5.000) = 7158 
    [ 5.000,  7.500) = 170 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.351 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.608          ops/ms
ClientSimple.existUser                       thrpt         12.412          ops/ms
ClientSimple.getUser                         thrpt         14.330          ops/ms
ClientSimple.listUser                        thrpt          8.595          ops/ms
ClientSimple.createUser                       avgt          1.999           ms/op
ClientSimple.existUser                        avgt          1.918           ms/op
ClientSimple.getUser                          avgt          1.957           ms/op
ClientSimple.listUser                         avgt          3.101           ms/op
ClientSimple.createUser                     sample  17446   1.833 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.423           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.651           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.167           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.376           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.993           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.908           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.876           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.949           ms/op
ClientSimple.existUser                      sample  16333   2.006 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.608           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.905           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.781           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.243           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.861           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.117           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.200           ms/op
ClientSimple.getUser                        sample  16616   1.929 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.663           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.761           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.462           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.687           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.518           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.577           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.234           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.495           ms/op
ClientSimple.listUser                       sample   9897   3.227 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.924           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.219           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.051           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.351           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.710           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.578           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.823           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.823           ms/op

Benchmark result is saved to 1720245922560.json
