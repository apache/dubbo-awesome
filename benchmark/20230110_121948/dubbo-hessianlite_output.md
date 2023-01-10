# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.642 ops/ms
Iteration   1: 1.188 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.188 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.539 ops/ms
Iteration   1: 3.329 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.329 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.166 ops/ms
Iteration   1: 2.767 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.767 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 0.668 ops/ms
Iteration   1: 0.826 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.826 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 25.764 ±(99.9%) 0.542 ms/op
Iteration   1: 16.904 ±(99.9%) 0.066 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.904 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 14.092 ±(99.9%) 0.238 ms/op
Iteration   1: 9.731 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.731 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 21.560 ±(99.9%) 0.402 ms/op
Iteration   1: 9.584 ±(99.9%) 0.052 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.584 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 41.455 ±(99.9%) 0.783 ms/op
Iteration   1: 25.348 ±(99.9%) 0.178 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  25.348 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 21.140 ±(99.9%) 0.577 ms/op
Iteration   1: 11.032 ±(99.9%) 0.249 ms/op
                 createUser·p0.00:   3.826 ms/op
                 createUser·p0.50:   10.387 ms/op
                 createUser·p0.90:   15.458 ms/op
                 createUser·p0.95:   19.464 ms/op
                 createUser·p0.99:   30.517 ms/op
                 createUser·p0.999:  32.342 ms/op
                 createUser·p0.9999: 33.063 ms/op
                 createUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 2934
  mean =     11.032 ±(99.9%) 0.249 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 3 
    [ 5.000,  7.500) = 190 
    [ 7.500, 10.000) = 1065 
    [10.000, 12.500) = 1118 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.826 ms/op
     p(50.0000) =     10.387 ms/op
     p(90.0000) =     15.458 ms/op
     p(95.0000) =     19.464 ms/op
     p(99.0000) =     30.517 ms/op
     p(99.9000) =     32.342 ms/op
     p(99.9900) =     33.063 ms/op
     p(99.9990) =     33.063 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 13.262 ±(99.9%) 0.359 ms/op
Iteration   1: 6.746 ±(99.9%) 0.129 ms/op
                 existUser·p0.00:   1.851 ms/op
                 existUser·p0.50:   6.160 ms/op
                 existUser·p0.90:   9.339 ms/op
                 existUser·p0.95:   10.889 ms/op
                 existUser·p0.99:   17.498 ms/op
                 existUser·p0.999:  24.822 ms/op
                 existUser·p0.9999: 25.461 ms/op
                 existUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4747
  mean =      6.746 ±(99.9%) 0.129 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 590 
    [ 5.000,  7.500) = 3037 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      6.160 ms/op
     p(90.0000) =      9.339 ms/op
     p(95.0000) =     10.889 ms/op
     p(99.0000) =     17.498 ms/op
     p(99.9000) =     24.822 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 18.447 ±(99.9%) 0.432 ms/op
Iteration   1: 8.383 ±(99.9%) 0.204 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   8.036 ms/op
                 getUser·p0.90:   12.735 ms/op
                 getUser·p0.95:   14.280 ms/op
                 getUser·p0.99:   19.792 ms/op
                 getUser·p0.999:  34.406 ms/op
                 getUser·p0.9999: 34.472 ms/op
                 getUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 3856
  mean =      8.383 ±(99.9%) 0.204 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 710 
    [ 5.000,  7.500) = 1081 
    [ 7.500, 10.000) = 970 
    [10.000, 12.500) = 661 
    [12.500, 15.000) = 316 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.655 ms/op
     p(50.0000) =      8.036 ms/op
     p(90.0000) =     12.735 ms/op
     p(95.0000) =     14.280 ms/op
     p(99.0000) =     19.792 ms/op
     p(99.9000) =     34.406 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 33.921 ±(99.9%) 1.167 ms/op
Iteration   1: 27.644 ±(99.9%) 0.514 ms/op
                 listUser·p0.00:   10.109 ms/op
                 listUser·p0.50:   29.032 ms/op
                 listUser·p0.90:   32.997 ms/op
                 listUser·p0.95:   35.576 ms/op
                 listUser·p0.99:   40.076 ms/op
                 listUser·p0.999:  46.852 ms/op
                 listUser·p0.9999: 46.924 ms/op
                 listUser·p1.00:   46.924 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1182
  mean =     27.644 ±(99.9%) 0.514 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 220 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 128 
    [27.500, 30.000) = 222 
    [30.000, 32.500) = 316 
    [32.500, 35.000) = 87 
    [35.000, 37.500) = 30 
    [37.500, 40.000) = 21 
    [40.000, 42.500) = 6 
    [42.500, 45.000) = 3 
    [45.000, 47.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =     10.109 ms/op
     p(50.0000) =     29.032 ms/op
     p(90.0000) =     32.997 ms/op
     p(95.0000) =     35.576 ms/op
     p(99.0000) =     40.076 ms/op
     p(99.9000) =     46.852 ms/op
     p(99.9900) =     46.924 ms/op
     p(99.9990) =     46.924 ms/op
     p(99.9999) =     46.924 ms/op
    p(100.0000) =     46.924 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.188          ops/ms
Client.existUser                       thrpt         3.329          ops/ms
Client.getUser                         thrpt         2.767          ops/ms
Client.listUser                        thrpt         0.826          ops/ms
Client.createUser                       avgt        16.904           ms/op
Client.existUser                        avgt         9.731           ms/op
Client.getUser                          avgt         9.584           ms/op
Client.listUser                         avgt        25.348           ms/op
Client.createUser                     sample  2934  11.032 ± 0.249   ms/op
Client.createUser:createUser·p0.00    sample         3.826           ms/op
Client.createUser:createUser·p0.50    sample        10.387           ms/op
Client.createUser:createUser·p0.90    sample        15.458           ms/op
Client.createUser:createUser·p0.95    sample        19.464           ms/op
Client.createUser:createUser·p0.99    sample        30.517           ms/op
Client.createUser:createUser·p0.999   sample        32.342           ms/op
Client.createUser:createUser·p0.9999  sample        33.063           ms/op
Client.createUser:createUser·p1.00    sample        33.063           ms/op
Client.existUser                      sample  4747   6.746 ± 0.129   ms/op
Client.existUser:existUser·p0.00      sample         1.851           ms/op
Client.existUser:existUser·p0.50      sample         6.160           ms/op
Client.existUser:existUser·p0.90      sample         9.339           ms/op
Client.existUser:existUser·p0.95      sample        10.889           ms/op
Client.existUser:existUser·p0.99      sample        17.498           ms/op
Client.existUser:existUser·p0.999     sample        24.822           ms/op
Client.existUser:existUser·p0.9999    sample        25.461           ms/op
Client.existUser:existUser·p1.00      sample        25.461           ms/op
Client.getUser                        sample  3856   8.383 ± 0.204   ms/op
Client.getUser:getUser·p0.00          sample         1.655           ms/op
Client.getUser:getUser·p0.50          sample         8.036           ms/op
Client.getUser:getUser·p0.90          sample        12.735           ms/op
Client.getUser:getUser·p0.95          sample        14.280           ms/op
Client.getUser:getUser·p0.99          sample        19.792           ms/op
Client.getUser:getUser·p0.999         sample        34.406           ms/op
Client.getUser:getUser·p0.9999        sample        34.472           ms/op
Client.getUser:getUser·p1.00          sample        34.472           ms/op
Client.listUser                       sample  1182  27.644 ± 0.514   ms/op
Client.listUser:listUser·p0.00        sample        10.109           ms/op
Client.listUser:listUser·p0.50        sample        29.032           ms/op
Client.listUser:listUser·p0.90        sample        32.997           ms/op
Client.listUser:listUser·p0.95        sample        35.576           ms/op
Client.listUser:listUser·p0.99        sample        40.076           ms/op
Client.listUser:listUser·p0.999       sample        46.852           ms/op
Client.listUser:listUser·p0.9999      sample        46.924           ms/op
Client.listUser:listUser·p1.00        sample        46.924           ms/op
