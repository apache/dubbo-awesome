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
# Warmup Iteration   1: 1.105 ops/ms
Iteration   1: 3.132 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.132 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.360 ops/ms
Iteration   1: 7.888 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.888 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.427 ops/ms
Iteration   1: 4.581 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.581 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 0.918 ops/ms
Iteration   1: 1.304 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.304 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 12.592 ±(99.9%) 0.324 ms/op
Iteration   1: 7.016 ±(99.9%) 0.218 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.016 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.698 ±(99.9%) 0.115 ms/op
Iteration   1: 3.254 ±(99.9%) 0.066 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.254 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.160 ±(99.9%) 0.406 ms/op
Iteration   1: 5.945 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.945 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:39
# Fork: 1 of 1
# Warmup Iteration   1: 30.666 ±(99.9%) 0.692 ms/op
Iteration   1: 21.004 ±(99.9%) 0.400 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  21.004 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.426 ±(99.9%) 0.435 ms/op
Iteration   1: 8.295 ±(99.9%) 0.253 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   6.701 ms/op
                 createUser·p0.90:   13.759 ms/op
                 createUser·p0.95:   17.888 ms/op
                 createUser·p0.99:   27.329 ms/op
                 createUser·p0.999:  54.961 ms/op
                 createUser·p0.9999: 55.902 ms/op
                 createUser·p1.00:   55.902 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3841
  mean =      8.295 ±(99.9%) 0.253 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 316 
    [ 5.000, 10.000) = 2792 
    [10.000, 15.000) = 427 
    [15.000, 20.000) = 171 
    [20.000, 25.000) = 75 
    [25.000, 30.000) = 45 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.688 ms/op
     p(50.0000) =      6.701 ms/op
     p(90.0000) =     13.759 ms/op
     p(95.0000) =     17.888 ms/op
     p(99.0000) =     27.329 ms/op
     p(99.9000) =     54.961 ms/op
     p(99.9900) =     55.902 ms/op
     p(99.9990) =     55.902 ms/op
     p(99.9999) =     55.902 ms/op
    p(100.0000) =     55.902 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.188 ±(99.9%) 0.276 ms/op
Iteration   1: 3.191 ±(99.9%) 0.098 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.232 ms/op
                 existUser·p0.90:   5.341 ms/op
                 existUser·p0.95:   8.957 ms/op
                 existUser·p0.99:   13.550 ms/op
                 existUser·p0.999:  34.341 ms/op
                 existUser·p0.9999: 34.603 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9965
  mean =      3.191 ±(99.9%) 0.098 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6084 
    [ 2.500,  5.000) = 2748 
    [ 5.000,  7.500) = 505 
    [ 7.500, 10.000) = 194 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      8.957 ms/op
     p(99.0000) =     13.550 ms/op
     p(99.9000) =     34.341 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     34.603 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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
# Warmup Iteration   1: 12.282 ±(99.9%) 0.406 ms/op
Iteration   1: 5.161 ±(99.9%) 0.201 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   4.149 ms/op
                 getUser·p0.90:   7.250 ms/op
                 getUser·p0.95:   8.798 ms/op
                 getUser·p0.99:   16.949 ms/op
                 getUser·p0.999:  76.009 ms/op
                 getUser·p0.9999: 77.595 ms/op
                 getUser·p1.00:   77.595 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6094
  mean =      5.161 ±(99.9%) 0.201 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4404 
    [ 5.000, 10.000) = 1432 
    [10.000, 15.000) = 174 
    [15.000, 20.000) = 51 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 5 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 16 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      4.149 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.798 ms/op
     p(99.0000) =     16.949 ms/op
     p(99.9000) =     76.009 ms/op
     p(99.9900) =     77.595 ms/op
     p(99.9990) =     77.595 ms/op
     p(99.9999) =     77.595 ms/op
    p(100.0000) =     77.595 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:08
# Fork: 1 of 1
# Warmup Iteration   1: 25.941 ±(99.9%) 0.976 ms/op
Iteration   1: 17.013 ±(99.9%) 0.449 ms/op
                 listUser·p0.00:   2.675 ms/op
                 listUser·p0.50:   15.712 ms/op
                 listUser·p0.90:   24.117 ms/op
                 listUser·p0.95:   28.377 ms/op
                 listUser·p0.99:   40.174 ms/op
                 listUser·p0.999:  48.915 ms/op
                 listUser·p0.9999: 54.788 ms/op
                 listUser·p1.00:   54.788 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1869
  mean =     17.013 ±(99.9%) 0.449 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2 
    [ 5.000, 10.000) = 65 
    [10.000, 15.000) = 749 
    [15.000, 20.000) = 685 
    [20.000, 25.000) = 210 
    [25.000, 30.000) = 79 
    [30.000, 35.000) = 35 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 16 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.675 ms/op
     p(50.0000) =     15.712 ms/op
     p(90.0000) =     24.117 ms/op
     p(95.0000) =     28.377 ms/op
     p(99.0000) =     40.174 ms/op
     p(99.9000) =     48.915 ms/op
     p(99.9900) =     54.788 ms/op
     p(99.9990) =     54.788 ms/op
     p(99.9999) =     54.788 ms/op
    p(100.0000) =     54.788 ms/op


# Run complete. Total time: 00:01:36

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.132          ops/ms
Client.existUser                       thrpt         7.888          ops/ms
Client.getUser                         thrpt         4.581          ops/ms
Client.listUser                        thrpt         1.304          ops/ms
Client.createUser                       avgt         7.016           ms/op
Client.existUser                        avgt         3.254           ms/op
Client.getUser                          avgt         5.945           ms/op
Client.listUser                         avgt        21.004           ms/op
Client.createUser                     sample  3841   8.295 ± 0.253   ms/op
Client.createUser:createUser·p0.00    sample         1.688           ms/op
Client.createUser:createUser·p0.50    sample         6.701           ms/op
Client.createUser:createUser·p0.90    sample        13.759           ms/op
Client.createUser:createUser·p0.95    sample        17.888           ms/op
Client.createUser:createUser·p0.99    sample        27.329           ms/op
Client.createUser:createUser·p0.999   sample        54.961           ms/op
Client.createUser:createUser·p0.9999  sample        55.902           ms/op
Client.createUser:createUser·p1.00    sample        55.902           ms/op
Client.existUser                      sample  9965   3.191 ± 0.098   ms/op
Client.existUser:existUser·p0.00      sample         0.768           ms/op
Client.existUser:existUser·p0.50      sample         2.232           ms/op
Client.existUser:existUser·p0.90      sample         5.341           ms/op
Client.existUser:existUser·p0.95      sample         8.957           ms/op
Client.existUser:existUser·p0.99      sample        13.550           ms/op
Client.existUser:existUser·p0.999     sample        34.341           ms/op
Client.existUser:existUser·p0.9999    sample        34.603           ms/op
Client.existUser:existUser·p1.00      sample        34.603           ms/op
Client.getUser                        sample  6094   5.161 ± 0.201   ms/op
Client.getUser:getUser·p0.00          sample         0.529           ms/op
Client.getUser:getUser·p0.50          sample         4.149           ms/op
Client.getUser:getUser·p0.90          sample         7.250           ms/op
Client.getUser:getUser·p0.95          sample         8.798           ms/op
Client.getUser:getUser·p0.99          sample        16.949           ms/op
Client.getUser:getUser·p0.999         sample        76.009           ms/op
Client.getUser:getUser·p0.9999        sample        77.595           ms/op
Client.getUser:getUser·p1.00          sample        77.595           ms/op
Client.listUser                       sample  1869  17.013 ± 0.449   ms/op
Client.listUser:listUser·p0.00        sample         2.675           ms/op
Client.listUser:listUser·p0.50        sample        15.712           ms/op
Client.listUser:listUser·p0.90        sample        24.117           ms/op
Client.listUser:listUser·p0.95        sample        28.377           ms/op
Client.listUser:listUser·p0.99        sample        40.174           ms/op
Client.listUser:listUser·p0.999       sample        48.915           ms/op
Client.listUser:listUser·p0.9999      sample        54.788           ms/op
Client.listUser:listUser·p1.00        sample        54.788           ms/op
