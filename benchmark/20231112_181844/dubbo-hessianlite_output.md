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
# Warmup Iteration   1: 1.483 ops/ms
Iteration   1: 4.064 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.064 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:22
# Fork: 1 of 1
# Warmup Iteration   1: 4.868 ops/ms
Iteration   1: 12.762 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.762 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.291 ops/ms
Iteration   1: 7.420 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.420 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.102 ops/ms
Iteration   1: 1.879 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.879 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.942 ±(99.9%) 0.185 ms/op
Iteration   1: 3.510 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.510 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:52
# Fork: 1 of 1
# Warmup Iteration   1: 5.873 ±(99.9%) 0.062 ms/op
Iteration   1: 2.245 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.245 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.105 ±(99.9%) 0.143 ms/op
Iteration   1: 3.673 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.673 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 22.475 ±(99.9%) 0.542 ms/op
Iteration   1: 14.829 ±(99.9%) 0.196 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  14.829 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.961 ±(99.9%) 0.173 ms/op
Iteration   1: 4.699 ±(99.9%) 0.148 ms/op
                 createUser·p0.00:   1.239 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   9.175 ms/op
                 createUser·p0.95:   11.633 ms/op
                 createUser·p0.99:   19.464 ms/op
                 createUser·p0.999:  32.275 ms/op
                 createUser·p0.9999: 32.637 ms/op
                 createUser·p1.00:   32.637 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6808
  mean =      4.699 ±(99.9%) 0.148 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1277 
    [ 2.500,  5.000) = 3815 
    [ 5.000,  7.500) = 709 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.239 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      9.175 ms/op
     p(95.0000) =     11.633 ms/op
     p(99.0000) =     19.464 ms/op
     p(99.9000) =     32.275 ms/op
     p(99.9900) =     32.637 ms/op
     p(99.9990) =     32.637 ms/op
     p(99.9999) =     32.637 ms/op
    p(100.0000) =     32.637 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.842 ±(99.9%) 0.176 ms/op
Iteration   1: 1.949 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.581 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.249 ms/op
                 existUser·p0.95:   2.875 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  14.775 ms/op
                 existUser·p0.9999: 16.008 ms/op
                 existUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16593
  mean =      1.949 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 620 
    [ 1.250,  2.500) = 14932 
    [ 2.500,  3.750) = 500 
    [ 3.750,  5.000) = 238 
    [ 5.000,  6.250) = 177 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.249 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     14.775 ms/op
     p(99.9900) =     16.008 ms/op
     p(99.9990) =     16.040 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 7.197 ±(99.9%) 0.185 ms/op
Iteration   1: 2.906 ±(99.9%) 0.049 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  17.170 ms/op
                 getUser·p0.9999: 17.542 ms/op
                 getUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10964
  mean =      2.906 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 5817 
    [ 2.500,  3.750) = 3707 
    [ 3.750,  5.000) = 699 
    [ 5.000,  6.250) = 298 
    [ 6.250,  7.500) = 197 
    [ 7.500,  8.750) = 110 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     17.542 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 21.750 ±(99.9%) 0.685 ms/op
Iteration   1: 12.238 ±(99.9%) 0.226 ms/op
                 listUser·p0.00:   3.621 ms/op
                 listUser·p0.50:   11.928 ms/op
                 listUser·p0.90:   15.745 ms/op
                 listUser·p0.95:   17.498 ms/op
                 listUser·p0.99:   26.652 ms/op
                 listUser·p0.999:  33.540 ms/op
                 listUser·p0.9999: 71.565 ms/op
                 listUser·p1.00:   71.565 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2643
  mean =     12.238 ±(99.9%) 0.226 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8 
    [ 5.000, 10.000) = 545 
    [10.000, 15.000) = 1735 
    [15.000, 20.000) = 293 
    [20.000, 25.000) = 25 
    [25.000, 30.000) = 29 
    [30.000, 35.000) = 7 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.621 ms/op
     p(50.0000) =     11.928 ms/op
     p(90.0000) =     15.745 ms/op
     p(95.0000) =     17.498 ms/op
     p(99.0000) =     26.652 ms/op
     p(99.9000) =     33.540 ms/op
     p(99.9900) =     71.565 ms/op
     p(99.9990) =     71.565 ms/op
     p(99.9999) =     71.565 ms/op
    p(100.0000) =     71.565 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.064          ops/ms
Client.existUser                       thrpt         12.762          ops/ms
Client.getUser                         thrpt          7.420          ops/ms
Client.listUser                        thrpt          1.879          ops/ms
Client.createUser                       avgt          3.510           ms/op
Client.existUser                        avgt          2.245           ms/op
Client.getUser                          avgt          3.673           ms/op
Client.listUser                         avgt         14.829           ms/op
Client.createUser                     sample   6808   4.699 ± 0.148   ms/op
Client.createUser:createUser·p0.00    sample          1.239           ms/op
Client.createUser:createUser·p0.50    sample          3.355           ms/op
Client.createUser:createUser·p0.90    sample          9.175           ms/op
Client.createUser:createUser·p0.95    sample         11.633           ms/op
Client.createUser:createUser·p0.99    sample         19.464           ms/op
Client.createUser:createUser·p0.999   sample         32.275           ms/op
Client.createUser:createUser·p0.9999  sample         32.637           ms/op
Client.createUser:createUser·p1.00    sample         32.637           ms/op
Client.existUser                      sample  16593   1.949 ± 0.026   ms/op
Client.existUser:existUser·p0.00      sample          0.581           ms/op
Client.existUser:existUser·p0.50      sample          1.788           ms/op
Client.existUser:existUser·p0.90      sample          2.249           ms/op
Client.existUser:existUser·p0.95      sample          2.875           ms/op
Client.existUser:existUser·p0.99      sample          5.816           ms/op
Client.existUser:existUser·p0.999     sample         14.775           ms/op
Client.existUser:existUser·p0.9999    sample         16.008           ms/op
Client.existUser:existUser·p1.00      sample         16.040           ms/op
Client.getUser                        sample  10964   2.906 ± 0.049   ms/op
Client.getUser:getUser·p0.00          sample          0.729           ms/op
Client.getUser:getUser·p0.50          sample          2.470           ms/op
Client.getUser:getUser·p0.90          sample          4.100           ms/op
Client.getUser:getUser·p0.95          sample          5.751           ms/op
Client.getUser:getUser·p0.99          sample          8.765           ms/op
Client.getUser:getUser·p0.999         sample         17.170           ms/op
Client.getUser:getUser·p0.9999        sample         17.542           ms/op
Client.getUser:getUser·p1.00          sample         17.564           ms/op
Client.listUser                       sample   2643  12.238 ± 0.226   ms/op
Client.listUser:listUser·p0.00        sample          3.621           ms/op
Client.listUser:listUser·p0.50        sample         11.928           ms/op
Client.listUser:listUser·p0.90        sample         15.745           ms/op
Client.listUser:listUser·p0.95        sample         17.498           ms/op
Client.listUser:listUser·p0.99        sample         26.652           ms/op
Client.listUser:listUser·p0.999       sample         33.540           ms/op
Client.listUser:listUser·p0.9999      sample         71.565           ms/op
Client.listUser:listUser·p1.00        sample         71.565           ms/op
