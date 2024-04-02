# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.940 ops/ms
Iteration   1: 7.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.347 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.907 ops/ms
Iteration   1: 12.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.228 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.388 ops/ms
Iteration   1: 12.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.468 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.452 ops/ms
Iteration   1: 8.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.653 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.686 ±(99.9%) 0.071 ms/op
Iteration   1: 2.094 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.094 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.253 ±(99.9%) 0.044 ms/op
Iteration   1: 1.919 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.919 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.565 ±(99.9%) 0.055 ms/op
Iteration   1: 1.991 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.991 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.099 ±(99.9%) 0.077 ms/op
Iteration   1: 3.776 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.776 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.723 ±(99.9%) 0.089 ms/op
Iteration   1: 2.293 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   2.134 ms/op
                 createUser·p0.90:   2.720 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   10.831 ms/op
                 createUser·p0.999:  14.536 ms/op
                 createUser·p0.9999: 19.792 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13946
  mean =      2.293 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 251 
    [ 1.250,  2.500) = 10868 
    [ 2.500,  3.750) = 2545 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =     10.831 ms/op
     p(99.9000) =     14.536 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.959 ±(99.9%) 0.075 ms/op
Iteration   1: 2.332 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.648 ms/op
                 existUser·p0.50:   2.118 ms/op
                 existUser·p0.90:   2.781 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   7.183 ms/op
                 existUser·p0.999:  22.807 ms/op
                 existUser·p0.9999: 23.503 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13720
  mean =      2.332 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11101 
    [ 2.500,  5.000) = 2340 
    [ 5.000,  7.500) = 161 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.648 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.781 ms/op
     p(95.0000) =      3.461 ms/op
     p(99.0000) =      7.183 ms/op
     p(99.9000) =     22.807 ms/op
     p(99.9900) =     23.503 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.271 ±(99.9%) 0.082 ms/op
Iteration   1: 2.047 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.476 ms/op
                 getUser·p0.50:   1.898 ms/op
                 getUser·p0.90:   2.314 ms/op
                 getUser·p0.95:   2.519 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  21.934 ms/op
                 getUser·p0.9999: 22.882 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15639
  mean =      2.047 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14831 
    [ 2.500,  5.000) = 649 
    [ 5.000,  7.500) = 91 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =     21.934 ms/op
     p(99.9900) =     22.882 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.152 ±(99.9%) 0.117 ms/op
Iteration   1: 3.736 ±(99.9%) 0.072 ms/op
                 listUser·p0.00:   0.944 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.981 ms/op
                 listUser·p0.99:   8.338 ms/op
                 listUser·p0.999:  32.549 ms/op
                 listUser·p0.9999: 33.620 ms/op
                 listUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8558
  mean =      3.736 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 699 
    [ 2.500,  5.000) = 7451 
    [ 5.000,  7.500) = 289 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      8.338 ms/op
     p(99.9000) =     32.549 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     33.620 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.347          ops/ms
ClientSimple.existUser                       thrpt         12.228          ops/ms
ClientSimple.getUser                         thrpt         12.468          ops/ms
ClientSimple.listUser                        thrpt          8.653          ops/ms
ClientSimple.createUser                       avgt          2.094           ms/op
ClientSimple.existUser                        avgt          1.919           ms/op
ClientSimple.getUser                          avgt          1.991           ms/op
ClientSimple.listUser                         avgt          3.776           ms/op
ClientSimple.createUser                     sample  13946   2.293 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.599           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.134           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.831           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.536           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.792           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.792           ms/op
ClientSimple.existUser                      sample  13720   2.332 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.648           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.118           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.781           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.461           ms/op
ClientSimple.existUser:existUser·p0.99      sample          7.183           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.807           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.503           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.527           ms/op
ClientSimple.getUser                        sample  15639   2.047 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.476           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.898           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.314           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.030           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.934           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.882           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.938           ms/op
ClientSimple.listUser                       sample   8558   3.736 ± 0.072   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.944           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.588           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.571           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.981           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.338           ms/op
ClientSimple.listUser:listUser·p0.999       sample         32.549           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         33.620           ms/op
ClientSimple.listUser:listUser·p1.00        sample         33.620           ms/op

Benchmark result is saved to 1712016897692.json
