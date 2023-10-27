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
# Warmup Iteration   1: 1.369 ops/ms
Iteration   1: 4.207 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.207 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 3.542 ops/ms
Iteration   1: 10.240 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.240 ops/ms


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
# Warmup Iteration   1: 2.112 ops/ms
Iteration   1: 4.634 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.634 ops/ms


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
# Warmup Iteration   1: 1.065 ops/ms
Iteration   1: 1.573 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.573 ops/ms


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
# Warmup Iteration   1: 9.894 ±(99.9%) 0.210 ms/op
Iteration   1: 4.908 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  4.908 ms/op


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
# Warmup Iteration   1: 6.608 ±(99.9%) 0.081 ms/op
Iteration   1: 2.454 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.454 ms/op


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
# Warmup Iteration   1: 11.304 ±(99.9%) 0.313 ms/op
Iteration   1: 5.184 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.184 ms/op


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
# Warmup Iteration   1: 24.275 ±(99.9%) 0.545 ms/op
Iteration   1: 17.113 ±(99.9%) 0.328 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.113 ms/op


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
# Warmup Iteration   1: 10.185 ±(99.9%) 0.263 ms/op
Iteration   1: 4.636 ±(99.9%) 0.174 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   8.389 ms/op
                 createUser·p0.95:   10.879 ms/op
                 createUser·p0.99:   15.731 ms/op
                 createUser·p0.999:  57.868 ms/op
                 createUser·p0.9999: 61.145 ms/op
                 createUser·p1.00:   61.145 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6987
  mean =      4.636 ±(99.9%) 0.174 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5351 
    [ 5.000, 10.000) = 1186 
    [10.000, 15.000) = 372 
    [15.000, 20.000) = 13 
    [20.000, 25.000) = 33 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 18 
    [55.000, 60.000) = 9 
    [60.000, 65.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      8.389 ms/op
     p(95.0000) =     10.879 ms/op
     p(99.0000) =     15.731 ms/op
     p(99.9000) =     57.868 ms/op
     p(99.9900) =     61.145 ms/op
     p(99.9990) =     61.145 ms/op
     p(99.9999) =     61.145 ms/op
    p(100.0000) =     61.145 ms/op


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
# Warmup Iteration   1: 6.894 ±(99.9%) 0.199 ms/op
Iteration   1: 2.402 ±(99.9%) 0.040 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.032 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   9.624 ms/op
                 existUser·p0.999:  17.007 ms/op
                 existUser·p0.9999: 17.613 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 13612
  mean =      2.402 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 11220 
    [ 2.500,  3.750) = 1553 
    [ 3.750,  5.000) = 281 
    [ 5.000,  6.250) = 110 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 144 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.032 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      9.624 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     17.613 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 9.737 ±(99.9%) 0.487 ms/op
Iteration   1: 4.171 ±(99.9%) 0.104 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   5.980 ms/op
                 getUser·p0.95:   8.325 ms/op
                 getUser·p0.99:   19.933 ms/op
                 getUser·p0.999:  24.379 ms/op
                 getUser·p0.9999: 25.395 ms/op
                 getUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7633
  mean =      4.171 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 726 
    [ 2.500,  5.000) = 5590 
    [ 5.000,  7.500) = 794 
    [ 7.500, 10.000) = 271 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      5.980 ms/op
     p(95.0000) =      8.325 ms/op
     p(99.0000) =     19.933 ms/op
     p(99.9000) =     24.379 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 23.468 ±(99.9%) 1.034 ms/op
Iteration   1: 17.403 ±(99.9%) 0.384 ms/op
                 listUser·p0.00:   5.161 ms/op
                 listUser·p0.50:   17.039 ms/op
                 listUser·p0.90:   22.961 ms/op
                 listUser·p0.95:   25.559 ms/op
                 listUser·p0.99:   39.289 ms/op
                 listUser·p0.999:  47.299 ms/op
                 listUser·p0.9999: 50.332 ms/op
                 listUser·p1.00:   50.332 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1872
  mean =     17.403 ±(99.9%) 0.384 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 53 
    [10.000, 15.000) = 490 
    [15.000, 20.000) = 956 
    [20.000, 25.000) = 266 
    [25.000, 30.000) = 60 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 15 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      5.161 ms/op
     p(50.0000) =     17.039 ms/op
     p(90.0000) =     22.961 ms/op
     p(95.0000) =     25.559 ms/op
     p(99.0000) =     39.289 ms/op
     p(99.9000) =     47.299 ms/op
     p(99.9900) =     50.332 ms/op
     p(99.9990) =     50.332 ms/op
     p(99.9999) =     50.332 ms/op
    p(100.0000) =     50.332 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          4.207          ops/ms
Client.existUser                       thrpt         10.240          ops/ms
Client.getUser                         thrpt          4.634          ops/ms
Client.listUser                        thrpt          1.573          ops/ms
Client.createUser                       avgt          4.908           ms/op
Client.existUser                        avgt          2.454           ms/op
Client.getUser                          avgt          5.184           ms/op
Client.listUser                         avgt         17.113           ms/op
Client.createUser                     sample   6987   4.636 ± 0.174   ms/op
Client.createUser:createUser·p0.00    sample          0.877           ms/op
Client.createUser:createUser·p0.50    sample          3.277           ms/op
Client.createUser:createUser·p0.90    sample          8.389           ms/op
Client.createUser:createUser·p0.95    sample         10.879           ms/op
Client.createUser:createUser·p0.99    sample         15.731           ms/op
Client.createUser:createUser·p0.999   sample         57.868           ms/op
Client.createUser:createUser·p0.9999  sample         61.145           ms/op
Client.createUser:createUser·p1.00    sample         61.145           ms/op
Client.existUser                      sample  13612   2.402 ± 0.040   ms/op
Client.existUser:existUser·p0.00      sample          0.862           ms/op
Client.existUser:existUser·p0.50      sample          2.032           ms/op
Client.existUser:existUser·p0.90      sample          2.933           ms/op
Client.existUser:existUser·p0.95      sample          4.227           ms/op
Client.existUser:existUser·p0.99      sample          9.624           ms/op
Client.existUser:existUser·p0.999     sample         17.007           ms/op
Client.existUser:existUser·p0.9999    sample         17.613           ms/op
Client.existUser:existUser·p1.00      sample         17.826           ms/op
Client.getUser                        sample   7633   4.171 ± 0.104   ms/op
Client.getUser:getUser·p0.00          sample          1.358           ms/op
Client.getUser:getUser·p0.50          sample          3.482           ms/op
Client.getUser:getUser·p0.90          sample          5.980           ms/op
Client.getUser:getUser·p0.95          sample          8.325           ms/op
Client.getUser:getUser·p0.99          sample         19.933           ms/op
Client.getUser:getUser·p0.999         sample         24.379           ms/op
Client.getUser:getUser·p0.9999        sample         25.395           ms/op
Client.getUser:getUser·p1.00          sample         25.395           ms/op
Client.listUser                       sample   1872  17.403 ± 0.384   ms/op
Client.listUser:listUser·p0.00        sample          5.161           ms/op
Client.listUser:listUser·p0.50        sample         17.039           ms/op
Client.listUser:listUser·p0.90        sample         22.961           ms/op
Client.listUser:listUser·p0.95        sample         25.559           ms/op
Client.listUser:listUser·p0.99        sample         39.289           ms/op
Client.listUser:listUser·p0.999       sample         47.299           ms/op
Client.listUser:listUser·p0.9999      sample         50.332           ms/op
Client.listUser:listUser·p1.00        sample         50.332           ms/op
