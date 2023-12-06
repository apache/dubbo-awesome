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
# Warmup Iteration   1: 1.927 ops/ms
Iteration   1: 5.153 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.153 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.524 ops/ms
Iteration   1: 11.479 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.479 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ops/ms
Iteration   1: 7.605 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.605 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.945 ops/ms
Iteration   1: 3.616 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.616 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 6.540 ±(99.9%) 0.104 ms/op
Iteration   1: 3.345 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.345 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.566 ±(99.9%) 0.038 ms/op
Iteration   1: 1.955 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.955 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.896 ±(99.9%) 0.061 ms/op
Iteration   1: 2.977 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.977 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.228 ±(99.9%) 0.191 ms/op
Iteration   1: 7.989 ±(99.9%) 0.067 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.989 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.549 ±(99.9%) 0.192 ms/op
Iteration   1: 3.171 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  11.611 ms/op
                 createUser·p0.9999: 12.756 ms/op
                 createUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10077
  mean =      3.171 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2105 
    [ 2.500,  3.750) = 6332 
    [ 3.750,  5.000) = 1390 
    [ 5.000,  6.250) = 137 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     11.611 ms/op
     p(99.9900) =     12.756 ms/op
     p(99.9990) =     12.763 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.173 ±(99.9%) 0.062 ms/op
Iteration   1: 1.903 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   1.806 ms/op
                 existUser·p0.90:   2.179 ms/op
                 existUser·p0.95:   2.351 ms/op
                 existUser·p0.99:   3.970 ms/op
                 existUser·p0.999:  24.674 ms/op
                 existUser·p0.9999: 25.495 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16812
  mean =      1.903 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16228 
    [ 2.500,  5.000) = 434 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.179 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      3.970 ms/op
     p(99.9000) =     24.674 ms/op
     p(99.9900) =     25.495 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.787 ±(99.9%) 0.248 ms/op
Iteration   1: 3.137 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.053 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  6.906 ms/op
                 getUser·p0.9999: 7.935 ms/op
                 getUser·p1.00:   7.938 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10201
  mean =      3.137 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 231 
    [2.000, 2.500) = 1982 
    [2.500, 3.000) = 2524 
    [3.000, 3.500) = 2546 
    [3.500, 4.000) = 1676 
    [4.000, 4.500) = 846 
    [4.500, 5.000) = 208 
    [5.000, 5.500) = 83 
    [5.500, 6.000) = 15 
    [6.000, 6.500) = 29 
    [6.500, 7.000) = 41 
    [7.000, 7.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =      6.906 ms/op
     p(99.9900) =      7.935 ms/op
     p(99.9990) =      7.938 ms/op
     p(99.9999) =      7.938 ms/op
    p(100.0000) =      7.938 ms/op


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
# Warmup Iteration   1: 14.032 ±(99.9%) 0.486 ms/op
Iteration   1: 8.454 ±(99.9%) 0.128 ms/op
                 listUser·p0.00:   3.486 ms/op
                 listUser·p0.50:   8.069 ms/op
                 listUser·p0.90:   11.203 ms/op
                 listUser·p0.95:   12.452 ms/op
                 listUser·p0.99:   17.838 ms/op
                 listUser·p0.999:  22.283 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3781
  mean =      8.454 ±(99.9%) 0.128 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 67 
    [ 5.000,  7.500) = 1410 
    [ 7.500, 10.000) = 1526 
    [10.000, 12.500) = 595 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.486 ms/op
     p(50.0000) =      8.069 ms/op
     p(90.0000) =     11.203 ms/op
     p(95.0000) =     12.452 ms/op
     p(99.0000) =     17.838 ms/op
     p(99.9000) =     22.283 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.153          ops/ms
Client.existUser                       thrpt         11.479          ops/ms
Client.getUser                         thrpt          7.605          ops/ms
Client.listUser                        thrpt          3.616          ops/ms
Client.createUser                       avgt          3.345           ms/op
Client.existUser                        avgt          1.955           ms/op
Client.getUser                          avgt          2.977           ms/op
Client.listUser                         avgt          7.989           ms/op
Client.createUser                     sample  10077   3.171 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          0.904           ms/op
Client.createUser:createUser·p0.50    sample          3.203           ms/op
Client.createUser:createUser·p0.90    sample          3.965           ms/op
Client.createUser:createUser·p0.95    sample          4.325           ms/op
Client.createUser:createUser·p0.99    sample          6.734           ms/op
Client.createUser:createUser·p0.999   sample         11.611           ms/op
Client.createUser:createUser·p0.9999  sample         12.756           ms/op
Client.createUser:createUser·p1.00    sample         12.763           ms/op
Client.existUser                      sample  16812   1.903 ± 0.028   ms/op
Client.existUser:existUser·p0.00      sample          0.796           ms/op
Client.existUser:existUser·p0.50      sample          1.806           ms/op
Client.existUser:existUser·p0.90      sample          2.179           ms/op
Client.existUser:existUser·p0.95      sample          2.351           ms/op
Client.existUser:existUser·p0.99      sample          3.970           ms/op
Client.existUser:existUser·p0.999     sample         24.674           ms/op
Client.existUser:existUser·p0.9999    sample         25.495           ms/op
Client.existUser:existUser·p1.00      sample         25.919           ms/op
Client.getUser                        sample  10201   3.137 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          1.053           ms/op
Client.getUser:getUser·p0.50          sample          3.072           ms/op
Client.getUser:getUser·p0.90          sample          4.096           ms/op
Client.getUser:getUser·p0.95          sample          4.391           ms/op
Client.getUser:getUser·p0.99          sample          5.366           ms/op
Client.getUser:getUser·p0.999         sample          6.906           ms/op
Client.getUser:getUser·p0.9999        sample          7.935           ms/op
Client.getUser:getUser·p1.00          sample          7.938           ms/op
Client.listUser                       sample   3781   8.454 ± 0.128   ms/op
Client.listUser:listUser·p0.00        sample          3.486           ms/op
Client.listUser:listUser·p0.50        sample          8.069           ms/op
Client.listUser:listUser·p0.90        sample         11.203           ms/op
Client.listUser:listUser·p0.95        sample         12.452           ms/op
Client.listUser:listUser·p0.99        sample         17.838           ms/op
Client.listUser:listUser·p0.999       sample         22.283           ms/op
Client.listUser:listUser·p0.9999      sample         23.364           ms/op
Client.listUser:listUser·p1.00        sample         23.364           ms/op
