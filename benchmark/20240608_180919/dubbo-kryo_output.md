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
# Warmup Iteration   1: 0.821 ops/ms
Iteration   1: 6.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.332 ops/ms


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
# Warmup Iteration   1: 5.429 ops/ms
Iteration   1: 11.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.648 ops/ms


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
# Warmup Iteration   1: 5.745 ops/ms
Iteration   1: 12.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.943 ops/ms


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
# Warmup Iteration   1: 4.738 ops/ms
Iteration   1: 8.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.483 ops/ms


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
# Warmup Iteration   1: 4.643 ±(99.9%) 0.098 ms/op
Iteration   1: 2.179 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.179 ms/op


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
# Warmup Iteration   1: 3.620 ±(99.9%) 0.063 ms/op
Iteration   1: 1.889 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.889 ms/op


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.071 ms/op
Iteration   1: 2.269 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.269 ms/op


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
# Warmup Iteration   1: 4.570 ±(99.9%) 0.098 ms/op
Iteration   1: 3.859 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.859 ms/op


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.099 ms/op
Iteration   1: 2.522 ±(99.9%) 0.068 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   2.208 ms/op
                 createUser·p0.90:   2.953 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  38.492 ms/op
                 createUser·p0.9999: 39.802 ms/op
                 createUser·p1.00:   40.239 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12664
  mean =      2.522 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12458 
    [ 5.000, 10.000) = 106 
    [10.000, 15.000) = 20 
    [15.000, 20.000) = 19 
    [20.000, 25.000) = 12 
    [25.000, 30.000) = 16 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      2.208 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     38.492 ms/op
     p(99.9900) =     39.802 ms/op
     p(99.9990) =     40.239 ms/op
     p(99.9999) =     40.239 ms/op
    p(100.0000) =     40.239 ms/op


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
# Warmup Iteration   1: 3.388 ±(99.9%) 0.096 ms/op
Iteration   1: 2.056 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   1.921 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  13.819 ms/op
                 existUser·p0.9999: 14.609 ms/op
                 existUser·p1.00:   14.664 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15545
  mean =      2.056 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 13925 
    [ 2.500,  3.750) = 1321 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 81 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =     13.819 ms/op
     p(99.9900) =     14.609 ms/op
     p(99.9990) =     14.664 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 3.700 ±(99.9%) 0.111 ms/op
Iteration   1: 2.345 ±(99.9%) 0.039 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   2.195 ms/op
                 getUser·p0.90:   2.904 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  26.804 ms/op
                 getUser·p0.9999: 27.358 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13715
  mean =      2.345 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9894 
    [ 2.500,  5.000) = 3678 
    [ 5.000,  7.500) = 77 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      2.904 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =     26.804 ms/op
     p(99.9900) =     27.358 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 4.547 ±(99.9%) 0.144 ms/op
Iteration   1: 3.703 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.777 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  10.551 ms/op
                 listUser·p0.9999: 10.912 ms/op
                 listUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8633
  mean =      3.703 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 369 
    [ 2.500,  3.750) = 4325 
    [ 3.750,  5.000) = 3622 
    [ 5.000,  6.250) = 184 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     10.912 ms/op
     p(99.9990) =     10.912 ms/op
     p(99.9999) =     10.912 ms/op
    p(100.0000) =     10.912 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.332          ops/ms
ClientSimple.existUser                       thrpt         11.648          ops/ms
ClientSimple.getUser                         thrpt         12.943          ops/ms
ClientSimple.listUser                        thrpt          8.483          ops/ms
ClientSimple.createUser                       avgt          2.179           ms/op
ClientSimple.existUser                        avgt          1.889           ms/op
ClientSimple.getUser                          avgt          2.269           ms/op
ClientSimple.listUser                         avgt          3.859           ms/op
ClientSimple.createUser                     sample  12664   2.522 ± 0.068   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.002           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.208           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.953           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.490           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.906           ms/op
ClientSimple.createUser:createUser·p0.999   sample         38.492           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.802           ms/op
ClientSimple.createUser:createUser·p1.00    sample         40.239           ms/op
ClientSimple.existUser                      sample  15545   2.056 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.494           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.921           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.514           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.819           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.609           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.664           ms/op
ClientSimple.getUser                        sample  13715   2.345 ± 0.039   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.583           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.195           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.904           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.162           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.022           ms/op
ClientSimple.getUser:getUser·p0.999         sample         26.804           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         27.358           ms/op
ClientSimple.getUser:getUser·p1.00          sample         27.394           ms/op
ClientSimple.listUser                       sample   8633   3.703 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.777           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.703           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.342           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.784           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.315           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.551           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.912           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.912           ms/op

Benchmark result is saved to 1717869889298.json
