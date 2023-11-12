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
# Warmup Iteration   1: 1.414 ops/ms
Iteration   1: 4.435 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.435 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ops/ms
Iteration   1: 11.252 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.252 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.047 ops/ms
Iteration   1: 6.382 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  6.382 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.168 ops/ms
Iteration   1: 1.985 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.985 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 11.072 ±(99.9%) 0.202 ms/op
Iteration   1: 4.176 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.176 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.078 ±(99.9%) 0.109 ms/op
Iteration   1: 2.490 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.490 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.772 ±(99.9%) 0.176 ms/op
Iteration   1: 5.214 ±(99.9%) 0.081 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.214 ms/op


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
# Warmup Iteration   1: 23.904 ±(99.9%) 0.764 ms/op
Iteration   1: 15.864 ±(99.9%) 0.207 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  15.864 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.251 ±(99.9%) 0.213 ms/op
Iteration   1: 3.795 ±(99.9%) 0.080 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   6.283 ms/op
                 createUser·p0.95:   7.750 ms/op
                 createUser·p0.99:   13.616 ms/op
                 createUser·p0.999:  20.251 ms/op
                 createUser·p0.9999: 24.379 ms/op
                 createUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8396
  mean =      3.795 ±(99.9%) 0.080 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1798 
    [ 2.500,  5.000) = 5180 
    [ 5.000,  7.500) = 938 
    [ 7.500, 10.000) = 291 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      6.283 ms/op
     p(95.0000) =      7.750 ms/op
     p(99.0000) =     13.616 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     24.379 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 5.687 ±(99.9%) 0.168 ms/op
Iteration   1: 1.971 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   1.792 ms/op
                 existUser·p0.90:   2.345 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  15.343 ms/op
                 existUser·p0.9999: 15.837 ms/op
                 existUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16303
  mean =      1.971 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 690 
    [ 1.250,  2.500) = 14355 
    [ 2.500,  3.750) = 704 
    [ 3.750,  5.000) = 176 
    [ 5.000,  6.250) = 147 
    [ 6.250,  7.500) = 127 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.345 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     15.343 ms/op
     p(99.9900) =     15.837 ms/op
     p(99.9990) =     16.105 ms/op
     p(99.9999) =     16.105 ms/op
    p(100.0000) =     16.105 ms/op


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
# Warmup Iteration   1: 7.470 ±(99.9%) 0.208 ms/op
Iteration   1: 3.150 ±(99.9%) 0.068 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.634 ms/op
                 getUser·p0.90:   4.568 ms/op
                 getUser·p0.95:   6.832 ms/op
                 getUser·p0.99:   13.615 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 22.994 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10133
  mean =      3.150 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4151 
    [ 2.500,  5.000) = 5108 
    [ 5.000,  7.500) = 458 
    [ 7.500, 10.000) = 201 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      4.568 ms/op
     p(95.0000) =      6.832 ms/op
     p(99.0000) =     13.615 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     22.994 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 19.256 ±(99.9%) 0.711 ms/op
Iteration   1: 14.814 ±(99.9%) 0.317 ms/op
                 listUser·p0.00:   4.432 ms/op
                 listUser·p0.50:   14.041 ms/op
                 listUser·p0.90:   20.021 ms/op
                 listUser·p0.95:   23.542 ms/op
                 listUser·p0.99:   33.334 ms/op
                 listUser·p0.999:  44.663 ms/op
                 listUser·p0.9999: 47.645 ms/op
                 listUser·p1.00:   47.645 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2336
  mean =     14.814 ±(99.9%) 0.317 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1 
    [ 5.000, 10.000) = 195 
    [10.000, 15.000) = 1288 
    [15.000, 20.000) = 618 
    [20.000, 25.000) = 141 
    [25.000, 30.000) = 55 
    [30.000, 35.000) = 22 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      4.432 ms/op
     p(50.0000) =     14.041 ms/op
     p(90.0000) =     20.021 ms/op
     p(95.0000) =     23.542 ms/op
     p(99.0000) =     33.334 ms/op
     p(99.9000) =     44.663 ms/op
     p(99.9900) =     47.645 ms/op
     p(99.9990) =     47.645 ms/op
     p(99.9999) =     47.645 ms/op
    p(100.0000) =     47.645 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.435          ops/ms
Client.existUser                       thrpt         11.252          ops/ms
Client.getUser                         thrpt          6.382          ops/ms
Client.listUser                        thrpt          1.985          ops/ms
Client.createUser                       avgt          4.176           ms/op
Client.existUser                        avgt          2.490           ms/op
Client.getUser                          avgt          5.214           ms/op
Client.listUser                         avgt         15.864           ms/op
Client.createUser                     sample   8396   3.795 ± 0.080   ms/op
Client.createUser:createUser·p0.00    sample          1.204           ms/op
Client.createUser:createUser·p0.50    sample          2.998           ms/op
Client.createUser:createUser·p0.90    sample          6.283           ms/op
Client.createUser:createUser·p0.95    sample          7.750           ms/op
Client.createUser:createUser·p0.99    sample         13.616           ms/op
Client.createUser:createUser·p0.999   sample         20.251           ms/op
Client.createUser:createUser·p0.9999  sample         24.379           ms/op
Client.createUser:createUser·p1.00    sample         24.379           ms/op
Client.existUser                      sample  16303   1.971 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample          0.547           ms/op
Client.existUser:existUser·p0.50      sample          1.792           ms/op
Client.existUser:existUser·p0.90      sample          2.345           ms/op
Client.existUser:existUser·p0.95      sample          2.986           ms/op
Client.existUser:existUser·p0.99      sample          6.816           ms/op
Client.existUser:existUser·p0.999     sample         15.343           ms/op
Client.existUser:existUser·p0.9999    sample         15.837           ms/op
Client.existUser:existUser·p1.00      sample         16.105           ms/op
Client.getUser                        sample  10133   3.150 ± 0.068   ms/op
Client.getUser:getUser·p0.00          sample          0.764           ms/op
Client.getUser:getUser·p0.50          sample          2.634           ms/op
Client.getUser:getUser·p0.90          sample          4.568           ms/op
Client.getUser:getUser·p0.95          sample          6.832           ms/op
Client.getUser:getUser·p0.99          sample         13.615           ms/op
Client.getUser:getUser·p0.999         sample         19.268           ms/op
Client.getUser:getUser·p0.9999        sample         22.994           ms/op
Client.getUser:getUser·p1.00          sample         23.036           ms/op
Client.listUser                       sample   2336  14.814 ± 0.317   ms/op
Client.listUser:listUser·p0.00        sample          4.432           ms/op
Client.listUser:listUser·p0.50        sample         14.041           ms/op
Client.listUser:listUser·p0.90        sample         20.021           ms/op
Client.listUser:listUser·p0.95        sample         23.542           ms/op
Client.listUser:listUser·p0.99        sample         33.334           ms/op
Client.listUser:listUser·p0.999       sample         44.663           ms/op
Client.listUser:listUser·p0.9999      sample         47.645           ms/op
Client.listUser:listUser·p1.00        sample         47.645           ms/op
