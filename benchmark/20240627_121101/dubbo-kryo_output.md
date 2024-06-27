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
# Warmup Iteration   1: 2.129 ops/ms
Iteration   1: 7.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.416 ops/ms


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
# Warmup Iteration   1: 6.154 ops/ms
Iteration   1: 12.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.824 ops/ms


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
# Warmup Iteration   1: 5.027 ops/ms
Iteration   1: 13.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.907 ops/ms


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
# Warmup Iteration   1: 4.621 ops/ms
Iteration   1: 8.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.626 ops/ms


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.090 ms/op
Iteration   1: 2.026 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.026 ms/op


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
# Warmup Iteration   1: 2.986 ±(99.9%) 0.045 ms/op
Iteration   1: 1.821 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.821 ms/op


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
# Warmup Iteration   1: 3.370 ±(99.9%) 0.072 ms/op
Iteration   1: 1.865 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.865 ms/op


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
# Warmup Iteration   1: 4.464 ±(99.9%) 0.094 ms/op
Iteration   1: 3.763 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.763 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.084 ms/op
Iteration   1: 2.316 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   2.001 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   3.314 ms/op
                 createUser·p0.99:   10.133 ms/op
                 createUser·p0.999:  23.986 ms/op
                 createUser·p0.9999: 24.137 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13855
  mean =      2.316 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11875 
    [ 2.500,  5.000) = 1594 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      3.314 ms/op
     p(99.0000) =     10.133 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     24.137 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 3.143 ±(99.9%) 0.078 ms/op
Iteration   1: 1.918 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   1.784 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.761 ms/op
                 existUser·p0.99:   4.769 ms/op
                 existUser·p0.999:  14.254 ms/op
                 existUser·p0.9999: 14.336 ms/op
                 existUser·p1.00:   14.336 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16691
  mean =      1.918 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 997 
    [ 1.250,  2.500) = 14305 
    [ 2.500,  3.750) = 1167 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.761 ms/op
     p(99.0000) =      4.769 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     14.336 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.485 ±(99.9%) 0.080 ms/op
Iteration   1: 2.062 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   1.880 ms/op
                 getUser·p0.90:   2.474 ms/op
                 getUser·p0.95:   2.695 ms/op
                 getUser·p0.99:   4.232 ms/op
                 getUser·p0.999:  23.069 ms/op
                 getUser·p0.9999: 23.877 ms/op
                 getUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15542
  mean =      2.062 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14117 
    [ 2.500,  5.000) = 1312 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      4.232 ms/op
     p(99.9000) =     23.069 ms/op
     p(99.9900) =     23.877 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 4.010 ±(99.9%) 0.111 ms/op
Iteration   1: 3.314 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.228 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   9.265 ms/op
                 listUser·p0.999:  11.928 ms/op
                 listUser·p0.9999: 13.615 ms/op
                 listUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9647
  mean =      3.314 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 1687 
    [ 2.500,  3.750) = 5912 
    [ 3.750,  5.000) = 1731 
    [ 5.000,  6.250) = 162 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      9.265 ms/op
     p(99.9000) =     11.928 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.416          ops/ms
ClientSimple.existUser                       thrpt         12.824          ops/ms
ClientSimple.getUser                         thrpt         13.907          ops/ms
ClientSimple.listUser                        thrpt          8.626          ops/ms
ClientSimple.createUser                       avgt          2.026           ms/op
ClientSimple.existUser                        avgt          1.821           ms/op
ClientSimple.getUser                          avgt          1.865           ms/op
ClientSimple.listUser                         avgt          3.763           ms/op
ClientSimple.createUser                     sample  13855   2.316 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.605           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.001           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.314           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.133           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.986           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.137           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.150           ms/op
ClientSimple.existUser                      sample  16691   1.918 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.555           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.784           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.761           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.769           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.254           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.336           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.336           ms/op
ClientSimple.getUser                        sample  15542   2.062 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.621           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.880           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.474           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.695           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.232           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.069           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.877           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.986           ms/op
ClientSimple.listUser                       sample   9647   3.314 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.087           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.228           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.153           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.265           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.928           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.615           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.615           ms/op

Benchmark result is saved to 1719490016387.json
