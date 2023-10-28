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
# Warmup Iteration   1: 1.106 ops/ms
Iteration   1: 2.895 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.895 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:29
# Fork: 1 of 1
# Warmup Iteration   1: 2.758 ops/ms
Iteration   1: 6.187 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.187 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 1.961 ops/ms
Iteration   1: 4.551 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.551 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 0.927 ops/ms
Iteration   1: 1.336 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.336 ops/ms


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
# Warmup Iteration   1: 13.807 ±(99.9%) 0.350 ms/op
Iteration   1: 6.916 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.916 ms/op


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
# Warmup Iteration   1: 7.935 ±(99.9%) 0.149 ms/op
Iteration   1: 3.626 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.626 ms/op


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
# Warmup Iteration   1: 12.008 ±(99.9%) 0.195 ms/op
Iteration   1: 5.937 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.937 ms/op


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
# Warmup Iteration   1: 33.011 ±(99.9%) 1.196 ms/op
Iteration   1: 23.049 ±(99.9%) 0.405 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  23.049 ms/op


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
# Warmup Iteration   1: 15.072 ±(99.9%) 0.555 ms/op
Iteration   1: 6.945 ±(99.9%) 0.225 ms/op
                 createUser·p0.00:   1.989 ms/op
                 createUser·p0.50:   4.805 ms/op
                 createUser·p0.90:   12.550 ms/op
                 createUser·p0.95:   16.876 ms/op
                 createUser·p0.99:   24.510 ms/op
                 createUser·p0.999:  29.222 ms/op
                 createUser·p0.9999: 29.393 ms/op
                 createUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4600
  mean =      6.945 ±(99.9%) 0.225 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 2423 
    [ 5.000,  7.500) = 765 
    [ 7.500, 10.000) = 631 
    [10.000, 12.500) = 298 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.989 ms/op
     p(50.0000) =      4.805 ms/op
     p(90.0000) =     12.550 ms/op
     p(95.0000) =     16.876 ms/op
     p(99.0000) =     24.510 ms/op
     p(99.9000) =     29.222 ms/op
     p(99.9900) =     29.393 ms/op
     p(99.9990) =     29.393 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 7.670 ±(99.9%) 0.253 ms/op
Iteration   1: 3.168 ±(99.9%) 0.095 ms/op
                 existUser·p0.00:   0.352 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   7.365 ms/op
                 existUser·p0.99:   12.890 ms/op
                 existUser·p0.999:  39.723 ms/op
                 existUser·p0.9999: 43.975 ms/op
                 existUser·p1.00:   43.975 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9937
  mean =      3.168 ±(99.9%) 0.095 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9225 
    [ 5.000, 10.000) = 392 
    [10.000, 15.000) = 222 
    [15.000, 20.000) = 65 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.352 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =     12.890 ms/op
     p(99.9000) =     39.723 ms/op
     p(99.9900) =     43.975 ms/op
     p(99.9990) =     43.975 ms/op
     p(99.9999) =     43.975 ms/op
    p(100.0000) =     43.975 ms/op


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
# Warmup Iteration   1: 10.954 ±(99.9%) 0.372 ms/op
Iteration   1: 4.970 ±(99.9%) 0.169 ms/op
                 getUser·p0.00:   1.284 ms/op
                 getUser·p0.50:   4.129 ms/op
                 getUser·p0.90:   6.128 ms/op
                 getUser·p0.95:   9.912 ms/op
                 getUser·p0.99:   19.056 ms/op
                 getUser·p0.999:  63.160 ms/op
                 getUser·p0.9999: 64.881 ms/op
                 getUser·p1.00:   64.881 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6564
  mean =      4.970 ±(99.9%) 0.169 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 5464 
    [ 5.000, 10.000) = 782 
    [10.000, 15.000) = 215 
    [15.000, 20.000) = 42 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 14 
    [30.000, 35.000) = 15 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 5 
    [60.000, 65.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      4.129 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      9.912 ms/op
     p(99.0000) =     19.056 ms/op
     p(99.9000) =     63.160 ms/op
     p(99.9900) =     64.881 ms/op
     p(99.9990) =     64.881 ms/op
     p(99.9999) =     64.881 ms/op
    p(100.0000) =     64.881 ms/op


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
# Warmup Iteration   1: 32.501 ±(99.9%) 1.304 ms/op
Iteration   1: 19.569 ±(99.9%) 0.541 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   18.940 ms/op
                 listUser·p0.90:   28.787 ms/op
                 listUser·p0.95:   30.482 ms/op
                 listUser·p0.99:   37.437 ms/op
                 listUser·p0.999:  60.621 ms/op
                 listUser·p0.9999: 61.866 ms/op
                 listUser·p1.00:   61.866 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1654
  mean =     19.569 ±(99.9%) 0.541 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 11 
    [ 5.000, 10.000) = 53 
    [10.000, 15.000) = 388 
    [15.000, 20.000) = 471 
    [20.000, 25.000) = 441 
    [25.000, 30.000) = 193 
    [30.000, 35.000) = 60 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 2 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =     18.940 ms/op
     p(90.0000) =     28.787 ms/op
     p(95.0000) =     30.482 ms/op
     p(99.0000) =     37.437 ms/op
     p(99.9000) =     60.621 ms/op
     p(99.9900) =     61.866 ms/op
     p(99.9990) =     61.866 ms/op
     p(99.9999) =     61.866 ms/op
    p(100.0000) =     61.866 ms/op


# Run complete. Total time: 00:01:36

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.895          ops/ms
Client.existUser                       thrpt         6.187          ops/ms
Client.getUser                         thrpt         4.551          ops/ms
Client.listUser                        thrpt         1.336          ops/ms
Client.createUser                       avgt         6.916           ms/op
Client.existUser                        avgt         3.626           ms/op
Client.getUser                          avgt         5.937           ms/op
Client.listUser                         avgt        23.049           ms/op
Client.createUser                     sample  4600   6.945 ± 0.225   ms/op
Client.createUser:createUser·p0.00    sample         1.989           ms/op
Client.createUser:createUser·p0.50    sample         4.805           ms/op
Client.createUser:createUser·p0.90    sample        12.550           ms/op
Client.createUser:createUser·p0.95    sample        16.876           ms/op
Client.createUser:createUser·p0.99    sample        24.510           ms/op
Client.createUser:createUser·p0.999   sample        29.222           ms/op
Client.createUser:createUser·p0.9999  sample        29.393           ms/op
Client.createUser:createUser·p1.00    sample        29.393           ms/op
Client.existUser                      sample  9937   3.168 ± 0.095   ms/op
Client.existUser:existUser·p0.00      sample         0.352           ms/op
Client.existUser:existUser·p0.50      sample         2.466           ms/op
Client.existUser:existUser·p0.90      sample         4.076           ms/op
Client.existUser:existUser·p0.95      sample         7.365           ms/op
Client.existUser:existUser·p0.99      sample        12.890           ms/op
Client.existUser:existUser·p0.999     sample        39.723           ms/op
Client.existUser:existUser·p0.9999    sample        43.975           ms/op
Client.existUser:existUser·p1.00      sample        43.975           ms/op
Client.getUser                        sample  6564   4.970 ± 0.169   ms/op
Client.getUser:getUser·p0.00          sample         1.284           ms/op
Client.getUser:getUser·p0.50          sample         4.129           ms/op
Client.getUser:getUser·p0.90          sample         6.128           ms/op
Client.getUser:getUser·p0.95          sample         9.912           ms/op
Client.getUser:getUser·p0.99          sample        19.056           ms/op
Client.getUser:getUser·p0.999         sample        63.160           ms/op
Client.getUser:getUser·p0.9999        sample        64.881           ms/op
Client.getUser:getUser·p1.00          sample        64.881           ms/op
Client.listUser                       sample  1654  19.569 ± 0.541   ms/op
Client.listUser:listUser·p0.00        sample         1.300           ms/op
Client.listUser:listUser·p0.50        sample        18.940           ms/op
Client.listUser:listUser·p0.90        sample        28.787           ms/op
Client.listUser:listUser·p0.95        sample        30.482           ms/op
Client.listUser:listUser·p0.99        sample        37.437           ms/op
Client.listUser:listUser·p0.999       sample        60.621           ms/op
Client.listUser:listUser·p0.9999      sample        61.866           ms/op
Client.listUser:listUser·p1.00        sample        61.866           ms/op
