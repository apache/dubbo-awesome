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
# Warmup Iteration   1: 2.353 ops/ms
Iteration   1: 6.573 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.573 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.312 ops/ms
Iteration   1: 11.748 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.748 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ops/ms
Iteration   1: 8.835 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.835 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.259 ops/ms
Iteration   1: 3.768 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.768 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.711 ±(99.9%) 0.099 ms/op
Iteration   1: 3.135 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.135 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.333 ±(99.9%) 0.030 ms/op
Iteration   1: 1.747 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.747 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.724 ±(99.9%) 0.051 ms/op
Iteration   1: 3.042 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.042 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.994 ±(99.9%) 0.193 ms/op
Iteration   1: 8.651 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.651 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.009 ±(99.9%) 0.117 ms/op
Iteration   1: 3.273 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   9.660 ms/op
                 createUser·p0.999:  16.785 ms/op
                 createUser·p0.9999: 18.383 ms/op
                 createUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9770
  mean =      3.273 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1766 
    [ 2.500,  3.750) = 6862 
    [ 3.750,  5.000) = 693 
    [ 5.000,  6.250) = 158 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      9.660 ms/op
     p(99.9000) =     16.785 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.055 ±(99.9%) 0.062 ms/op
Iteration   1: 1.826 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.410 ms/op
                 existUser·p0.50:   1.720 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   2.834 ms/op
                 existUser·p0.999:  18.481 ms/op
                 existUser·p0.9999: 18.743 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17518
  mean =      1.826 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 839 
    [ 1.250,  2.500) = 15813 
    [ 2.500,  3.750) = 782 
    [ 3.750,  5.000) = 11 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      1.720 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      2.834 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.237 ±(99.9%) 0.121 ms/op
Iteration   1: 3.381 ±(99.9%) 0.081 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.266 ms/op
                 getUser·p0.99:   5.224 ms/op
                 getUser·p0.999:  44.368 ms/op
                 getUser·p0.9999: 45.875 ms/op
                 getUser·p1.00:   45.875 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9465
  mean =      3.381 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9347 
    [ 5.000, 10.000) = 80 
    [10.000, 15.000) = 3 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.266 ms/op
     p(99.0000) =      5.224 ms/op
     p(99.9000) =     44.368 ms/op
     p(99.9900) =     45.875 ms/op
     p(99.9990) =     45.875 ms/op
     p(99.9999) =     45.875 ms/op
    p(100.0000) =     45.875 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.052 ±(99.9%) 0.364 ms/op
Iteration   1: 7.648 ±(99.9%) 0.129 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   7.193 ms/op
                 listUser·p0.90:   9.748 ms/op
                 listUser·p0.95:   10.945 ms/op
                 listUser·p0.99:   16.889 ms/op
                 listUser·p0.999:  28.958 ms/op
                 listUser·p0.9999: 32.276 ms/op
                 listUser·p1.00:   32.276 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4264
  mean =      7.648 ±(99.9%) 0.129 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 173 
    [ 5.000,  7.500) = 2298 
    [ 7.500, 10.000) = 1425 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.673 ms/op
     p(50.0000) =      7.193 ms/op
     p(90.0000) =      9.748 ms/op
     p(95.0000) =     10.945 ms/op
     p(99.0000) =     16.889 ms/op
     p(99.9000) =     28.958 ms/op
     p(99.9900) =     32.276 ms/op
     p(99.9990) =     32.276 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.573          ops/ms
Client.existUser                       thrpt         11.748          ops/ms
Client.getUser                         thrpt          8.835          ops/ms
Client.listUser                        thrpt          3.768          ops/ms
Client.createUser                       avgt          3.135           ms/op
Client.existUser                        avgt          1.747           ms/op
Client.getUser                          avgt          3.042           ms/op
Client.listUser                         avgt          8.651           ms/op
Client.createUser                     sample   9770   3.273 ± 0.051   ms/op
Client.createUser:createUser·p0.00    sample          1.184           ms/op
Client.createUser:createUser·p0.50    sample          3.047           ms/op
Client.createUser:createUser·p0.90    sample          3.813           ms/op
Client.createUser:createUser·p0.95    sample          4.661           ms/op
Client.createUser:createUser·p0.99    sample          9.660           ms/op
Client.createUser:createUser·p0.999   sample         16.785           ms/op
Client.createUser:createUser·p0.9999  sample         18.383           ms/op
Client.createUser:createUser·p1.00    sample         18.383           ms/op
Client.existUser                      sample  17518   1.826 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.410           ms/op
Client.existUser:existUser·p0.50      sample          1.720           ms/op
Client.existUser:existUser·p0.90      sample          2.380           ms/op
Client.existUser:existUser·p0.95      sample          2.499           ms/op
Client.existUser:existUser·p0.99      sample          2.834           ms/op
Client.existUser:existUser·p0.999     sample         18.481           ms/op
Client.existUser:existUser·p0.9999    sample         18.743           ms/op
Client.existUser:existUser·p1.00      sample         18.743           ms/op
Client.getUser                        sample   9465   3.381 ± 0.081   ms/op
Client.getUser:getUser·p0.00          sample          0.975           ms/op
Client.getUser:getUser·p0.50          sample          3.224           ms/op
Client.getUser:getUser·p0.90          sample          4.035           ms/op
Client.getUser:getUser·p0.95          sample          4.266           ms/op
Client.getUser:getUser·p0.99          sample          5.224           ms/op
Client.getUser:getUser·p0.999         sample         44.368           ms/op
Client.getUser:getUser·p0.9999        sample         45.875           ms/op
Client.getUser:getUser·p1.00          sample         45.875           ms/op
Client.listUser                       sample   4264   7.648 ± 0.129   ms/op
Client.listUser:listUser·p0.00        sample          1.673           ms/op
Client.listUser:listUser·p0.50        sample          7.193           ms/op
Client.listUser:listUser·p0.90        sample          9.748           ms/op
Client.listUser:listUser·p0.95        sample         10.945           ms/op
Client.listUser:listUser·p0.99        sample         16.889           ms/op
Client.listUser:listUser·p0.999       sample         28.958           ms/op
Client.listUser:listUser·p0.9999      sample         32.276           ms/op
Client.listUser:listUser·p1.00        sample         32.276           ms/op
