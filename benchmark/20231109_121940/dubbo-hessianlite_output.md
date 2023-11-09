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
# Warmup Iteration   1: 1.282 ops/ms
Iteration   1: 3.076 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.076 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.083 ops/ms
Iteration   1: 6.522 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.522 ops/ms


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
# Warmup Iteration   1: 2.050 ops/ms
Iteration   1: 3.982 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.982 ops/ms


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
# Warmup Iteration   1: 0.806 ops/ms
Iteration   1: 1.261 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.261 ops/ms


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
# Warmup Iteration   1: 11.008 ±(99.9%) 0.194 ms/op
Iteration   1: 5.452 ±(99.9%) 0.066 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.452 ms/op


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
# Warmup Iteration   1: 7.618 ±(99.9%) 0.129 ms/op
Iteration   1: 3.390 ±(99.9%) 0.056 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.390 ms/op


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
# Warmup Iteration   1: 11.018 ±(99.9%) 0.257 ms/op
Iteration   1: 5.100 ±(99.9%) 0.071 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.100 ms/op


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
# Warmup Iteration   1: 32.339 ±(99.9%) 0.882 ms/op
Iteration   1: 24.773 ±(99.9%) 0.448 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  24.773 ms/op


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
# Warmup Iteration   1: 11.499 ±(99.9%) 0.360 ms/op
Iteration   1: 5.033 ±(99.9%) 0.145 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   9.585 ms/op
                 createUser·p0.95:   11.387 ms/op
                 createUser·p0.99:   15.417 ms/op
                 createUser·p0.999:  33.777 ms/op
                 createUser·p0.9999: 39.256 ms/op
                 createUser·p1.00:   39.256 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 6299
  mean =      5.033 ±(99.9%) 0.145 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 450 
    [ 2.500,  5.000) = 3853 
    [ 5.000,  7.500) = 968 
    [ 7.500, 10.000) = 452 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      9.585 ms/op
     p(95.0000) =     11.387 ms/op
     p(99.0000) =     15.417 ms/op
     p(99.9000) =     33.777 ms/op
     p(99.9900) =     39.256 ms/op
     p(99.9990) =     39.256 ms/op
     p(99.9999) =     39.256 ms/op
    p(100.0000) =     39.256 ms/op


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
# Warmup Iteration   1: 7.061 ±(99.9%) 0.188 ms/op
Iteration   1: 2.959 ±(99.9%) 0.083 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   2.331 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   6.849 ms/op
                 existUser·p0.99:   13.615 ms/op
                 existUser·p0.999:  34.144 ms/op
                 existUser·p0.9999: 54.547 ms/op
                 existUser·p1.00:   54.788 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10966
  mean =      2.959 ±(99.9%) 0.083 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 10136 
    [ 5.000, 10.000) = 521 
    [10.000, 15.000) = 264 
    [15.000, 20.000) = 8 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      2.331 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      6.849 ms/op
     p(99.0000) =     13.615 ms/op
     p(99.9000) =     34.144 ms/op
     p(99.9900) =     54.547 ms/op
     p(99.9990) =     54.788 ms/op
     p(99.9999) =     54.788 ms/op
    p(100.0000) =     54.788 ms/op


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
# Warmup Iteration   1: 11.564 ±(99.9%) 0.567 ms/op
Iteration   1: 4.603 ±(99.9%) 0.112 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   6.578 ms/op
                 getUser·p0.95:   8.526 ms/op
                 getUser·p0.99:   17.903 ms/op
                 getUser·p0.999:  34.608 ms/op
                 getUser·p0.9999: 37.683 ms/op
                 getUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7091
  mean =      4.603 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 172 
    [ 2.500,  5.000) = 5572 
    [ 5.000,  7.500) = 812 
    [ 7.500, 10.000) = 314 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      8.526 ms/op
     p(99.0000) =     17.903 ms/op
     p(99.9000) =     34.608 ms/op
     p(99.9900) =     37.683 ms/op
     p(99.9990) =     37.683 ms/op
     p(99.9999) =     37.683 ms/op
    p(100.0000) =     37.683 ms/op


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
# Warmup Iteration   1: 27.543 ±(99.9%) 0.902 ms/op
Iteration   1: 18.206 ±(99.9%) 0.540 ms/op
                 listUser·p0.00:   3.707 ms/op
                 listUser·p0.50:   17.334 ms/op
                 listUser·p0.90:   26.424 ms/op
                 listUser·p0.95:   29.295 ms/op
                 listUser·p0.99:   46.407 ms/op
                 listUser·p0.999:  64.234 ms/op
                 listUser·p0.9999: 67.371 ms/op
                 listUser·p1.00:   67.371 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1771
  mean =     18.206 ±(99.9%) 0.540 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4 
    [ 5.000, 10.000) = 91 
    [10.000, 15.000) = 526 
    [15.000, 20.000) = 566 
    [20.000, 25.000) = 366 
    [25.000, 30.000) = 149 
    [30.000, 35.000) = 38 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 6 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 8 
    [60.000, 65.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      3.707 ms/op
     p(50.0000) =     17.334 ms/op
     p(90.0000) =     26.424 ms/op
     p(95.0000) =     29.295 ms/op
     p(99.0000) =     46.407 ms/op
     p(99.9000) =     64.234 ms/op
     p(99.9900) =     67.371 ms/op
     p(99.9990) =     67.371 ms/op
     p(99.9999) =     67.371 ms/op
    p(100.0000) =     67.371 ms/op


# Run complete. Total time: 00:01:35

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          3.076          ops/ms
Client.existUser                       thrpt          6.522          ops/ms
Client.getUser                         thrpt          3.982          ops/ms
Client.listUser                        thrpt          1.261          ops/ms
Client.createUser                       avgt          5.452           ms/op
Client.existUser                        avgt          3.390           ms/op
Client.getUser                          avgt          5.100           ms/op
Client.listUser                         avgt         24.773           ms/op
Client.createUser                     sample   6299   5.033 ± 0.145   ms/op
Client.createUser:createUser·p0.00    sample          1.278           ms/op
Client.createUser:createUser·p0.50    sample          3.731           ms/op
Client.createUser:createUser·p0.90    sample          9.585           ms/op
Client.createUser:createUser·p0.95    sample         11.387           ms/op
Client.createUser:createUser·p0.99    sample         15.417           ms/op
Client.createUser:createUser·p0.999   sample         33.777           ms/op
Client.createUser:createUser·p0.9999  sample         39.256           ms/op
Client.createUser:createUser·p1.00    sample         39.256           ms/op
Client.existUser                      sample  10966   2.959 ± 0.083   ms/op
Client.existUser:existUser·p0.00      sample          0.821           ms/op
Client.existUser:existUser·p0.50      sample          2.331           ms/op
Client.existUser:existUser·p0.90      sample          4.194           ms/op
Client.existUser:existUser·p0.95      sample          6.849           ms/op
Client.existUser:existUser·p0.99      sample         13.615           ms/op
Client.existUser:existUser·p0.999     sample         34.144           ms/op
Client.existUser:existUser·p0.9999    sample         54.547           ms/op
Client.existUser:existUser·p1.00      sample         54.788           ms/op
Client.getUser                        sample   7091   4.603 ± 0.112   ms/op
Client.getUser:getUser·p0.00          sample          1.391           ms/op
Client.getUser:getUser·p0.50          sample          3.944           ms/op
Client.getUser:getUser·p0.90          sample          6.578           ms/op
Client.getUser:getUser·p0.95          sample          8.526           ms/op
Client.getUser:getUser·p0.99          sample         17.903           ms/op
Client.getUser:getUser·p0.999         sample         34.608           ms/op
Client.getUser:getUser·p0.9999        sample         37.683           ms/op
Client.getUser:getUser·p1.00          sample         37.683           ms/op
Client.listUser                       sample   1771  18.206 ± 0.540   ms/op
Client.listUser:listUser·p0.00        sample          3.707           ms/op
Client.listUser:listUser·p0.50        sample         17.334           ms/op
Client.listUser:listUser·p0.90        sample         26.424           ms/op
Client.listUser:listUser·p0.95        sample         29.295           ms/op
Client.listUser:listUser·p0.99        sample         46.407           ms/op
Client.listUser:listUser·p0.999       sample         64.234           ms/op
Client.listUser:listUser·p0.9999      sample         67.371           ms/op
Client.listUser:listUser·p1.00        sample         67.371           ms/op
