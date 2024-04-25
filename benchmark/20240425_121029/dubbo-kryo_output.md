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
# Warmup Iteration   1: 2.004 ops/ms
Iteration   1: 7.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.153 ops/ms


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
# Warmup Iteration   1: 5.717 ops/ms
Iteration   1: 11.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.709 ops/ms


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
# Warmup Iteration   1: 6.205 ops/ms
Iteration   1: 13.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.700 ops/ms


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
# Warmup Iteration   1: 4.678 ops/ms
Iteration   1: 8.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.741 ops/ms


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
# Warmup Iteration   1: 3.647 ±(99.9%) 0.056 ms/op
Iteration   1: 2.138 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.138 ms/op


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
# Warmup Iteration   1: 3.219 ±(99.9%) 0.053 ms/op
Iteration   1: 2.129 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.129 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.048 ms/op
Iteration   1: 2.102 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.102 ms/op


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
# Warmup Iteration   1: 4.409 ±(99.9%) 0.096 ms/op
Iteration   1: 3.407 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.407 ms/op


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
# Warmup Iteration   1: 3.919 ±(99.9%) 0.106 ms/op
Iteration   1: 2.280 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.392 ms/op
                 createUser·p0.50:   2.052 ms/op
                 createUser·p0.90:   2.916 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   11.436 ms/op
                 createUser·p0.999:  18.675 ms/op
                 createUser·p0.9999: 18.927 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14087
  mean =      2.280 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 327 
    [ 1.250,  2.500) = 10894 
    [ 2.500,  3.750) = 2510 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.392 ms/op
     p(50.0000) =      2.052 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =     11.436 ms/op
     p(99.9000) =     18.675 ms/op
     p(99.9900) =     18.927 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 3.036 ±(99.9%) 0.069 ms/op
Iteration   1: 1.883 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.620 ms/op
                 existUser·p0.50:   1.800 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.451 ms/op
                 existUser·p0.99:   3.896 ms/op
                 existUser·p0.999:  19.497 ms/op
                 existUser·p0.9999: 19.973 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16973
  mean =      1.883 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16278 
    [ 2.500,  5.000) = 573 
    [ 5.000,  7.500) = 90 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      1.800 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.451 ms/op
     p(99.0000) =      3.896 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     19.973 ms/op
     p(99.9990) =     20.316 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.104 ms/op
Iteration   1: 1.910 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.527 ms/op
                 getUser·p0.50:   1.855 ms/op
                 getUser·p0.90:   2.363 ms/op
                 getUser·p0.95:   2.572 ms/op
                 getUser·p0.99:   3.697 ms/op
                 getUser·p0.999:  11.862 ms/op
                 getUser·p0.9999: 12.614 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16762
  mean =      1.910 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 685 
    [ 1.250,  2.500) = 15073 
    [ 2.500,  3.750) = 838 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      3.697 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     12.614 ms/op
     p(99.9990) =     12.714 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


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
# Warmup Iteration   1: 4.352 ±(99.9%) 0.139 ms/op
Iteration   1: 3.153 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.915 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.696 ms/op
                 listUser·p0.999:  19.067 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10132
  mean =      3.153 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 414 
    [ 2.500,  3.750) = 8369 
    [ 3.750,  5.000) = 1087 
    [ 5.000,  6.250) = 185 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.915 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.696 ms/op
     p(99.9000) =     19.067 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.153          ops/ms
ClientSimple.existUser                       thrpt         11.709          ops/ms
ClientSimple.getUser                         thrpt         13.700          ops/ms
ClientSimple.listUser                        thrpt          8.741          ops/ms
ClientSimple.createUser                       avgt          2.138           ms/op
ClientSimple.existUser                        avgt          2.129           ms/op
ClientSimple.getUser                          avgt          2.102           ms/op
ClientSimple.listUser                         avgt          3.407           ms/op
ClientSimple.createUser                     sample  14087   2.280 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.392           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.052           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.252           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.436           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.675           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.927           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.940           ms/op
ClientSimple.existUser                      sample  16973   1.883 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.620           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.800           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.257           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.451           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.896           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.497           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.973           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.316           ms/op
ClientSimple.getUser                        sample  16762   1.910 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.527           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.855           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.363           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.697           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.862           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.614           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.714           ms/op
ClientSimple.listUser                       sample  10132   3.153 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.204           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.925           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.915           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.696           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.067           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.104           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.104           ms/op

Benchmark result is saved to 1714046772205.json
