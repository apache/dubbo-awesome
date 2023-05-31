# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.693 ops/ms
# Warmup Iteration   2: 3.533 ops/ms
# Warmup Iteration   3: 7.057 ops/ms
Iteration   1: 7.283 ops/ms
Iteration   2: 8.451 ops/ms
Iteration   3: 8.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.044 ±(99.9%) 12.027 ops/ms [Average]
  (min, avg, max) = (7.283, 8.044, 8.451), stdev = 0.659
  CI (99.9%): [≈ 0, 20.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.422 ops/ms
# Warmup Iteration   2: 7.098 ops/ms
# Warmup Iteration   3: 8.294 ops/ms
Iteration   1: 8.638 ops/ms
Iteration   2: 8.336 ops/ms
Iteration   3: 8.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.519 ±(99.9%) 2.937 ops/ms [Average]
  (min, avg, max) = (8.336, 8.519, 8.638), stdev = 0.161
  CI (99.9%): [5.582, 11.456] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.162 ops/ms
# Warmup Iteration   2: 6.025 ops/ms
# Warmup Iteration   3: 7.705 ops/ms
Iteration   1: 8.066 ops/ms
Iteration   2: 8.231 ops/ms
Iteration   3: 8.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.162 ±(99.9%) 1.553 ops/ms [Average]
  (min, avg, max) = (8.066, 8.162, 8.231), stdev = 0.085
  CI (99.9%): [6.608, 9.715] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.336 ops/ms
# Warmup Iteration   2: 5.217 ops/ms
# Warmup Iteration   3: 6.672 ops/ms
Iteration   1: 7.093 ops/ms
Iteration   2: 7.047 ops/ms
Iteration   3: 6.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.021 ±(99.9%) 1.612 ops/ms [Average]
  (min, avg, max) = (6.922, 7.021, 7.093), stdev = 0.088
  CI (99.9%): [5.409, 8.632] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.788 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.530 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.287 ±(99.9%) 0.005 ms/op
Iteration   1: 3.938 ±(99.9%) 0.004 ms/op
Iteration   2: 3.923 ±(99.9%) 0.007 ms/op
Iteration   3: 4.014 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.958 ±(99.9%) 0.891 ms/op [Average]
  (min, avg, max) = (3.923, 3.958, 4.014), stdev = 0.049
  CI (99.9%): [3.067, 4.850] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.195 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.875 ±(99.9%) 0.005 ms/op
Iteration   1: 3.739 ±(99.9%) 0.014 ms/op
Iteration   2: 3.586 ±(99.9%) 0.012 ms/op
Iteration   3: 3.627 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.651 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (3.586, 3.651, 3.739), stdev = 0.079
  CI (99.9%): [2.209, 5.092] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.816 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.212 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.008 ms/op
Iteration   1: 3.898 ±(99.9%) 0.009 ms/op
Iteration   2: 3.962 ±(99.9%) 0.006 ms/op
Iteration   3: 3.811 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.890 ±(99.9%) 1.388 ms/op [Average]
  (min, avg, max) = (3.811, 3.890, 3.962), stdev = 0.076
  CI (99.9%): [2.502, 5.279] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.574 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.670 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.774 ±(99.9%) 0.008 ms/op
Iteration   1: 4.714 ±(99.9%) 0.012 ms/op
Iteration   2: 4.804 ±(99.9%) 0.010 ms/op
Iteration   3: 4.603 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.707 ±(99.9%) 1.840 ms/op [Average]
  (min, avg, max) = (4.603, 4.707, 4.804), stdev = 0.101
  CI (99.9%): [2.867, 6.547] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.751 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 5.149 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.390 ±(99.9%) 0.017 ms/op
Iteration   1: 3.798 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.849 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.327 ms/op
                 createUser·p0.999:  22.855 ms/op
                 createUser·p0.9999: 25.597 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   2: 4.011 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.423 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  25.213 ms/op
                 createUser·p0.9999: 31.754 ms/op
                 createUser·p1.00:   32.244 ms/op

Iteration   3: 3.899 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.802 ms/op
                 createUser·p0.50:   3.756 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.644 ms/op
                 createUser·p0.999:  11.976 ms/op
                 createUser·p0.9999: 32.997 ms/op
                 createUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246162
  mean =      3.901 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 517 
    [ 2.500,  5.000) = 235555 
    [ 5.000,  7.500) = 8648 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 290 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.423 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     22.741 ms/op
     p(99.9900) =     31.863 ms/op
     p(99.9990) =     33.098 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.448 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 4.233 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.011 ms/op
Iteration   1: 3.622 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.468 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  22.643 ms/op
                 existUser·p0.9999: 25.237 ms/op
                 existUser·p1.00:   25.657 ms/op

Iteration   2: 3.817 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.696 ms/op
                 existUser·p0.50:   3.617 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   7.750 ms/op
                 existUser·p0.999:  14.351 ms/op
                 existUser·p0.9999: 27.422 ms/op
                 existUser·p1.00:   28.705 ms/op

Iteration   3: 3.657 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  27.185 ms/op
                 existUser·p0.9999: 32.171 ms/op
                 existUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 259600
  mean =      3.697 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 673 
    [ 2.500,  5.000) = 251765 
    [ 5.000,  7.500) = 5772 
    [ 7.500, 10.000) = 922 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     16.037 ms/op
     p(99.9900) =     30.869 ms/op
     p(99.9990) =     32.592 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.426 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.573 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.063 ±(99.9%) 0.013 ms/op
Iteration   1: 3.858 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  22.090 ms/op
                 getUser·p0.9999: 25.484 ms/op
                 getUser·p1.00:   26.771 ms/op

Iteration   2: 3.774 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.062 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  12.640 ms/op
                 getUser·p0.9999: 27.215 ms/op
                 getUser·p1.00:   28.148 ms/op

Iteration   3: 4.003 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  27.460 ms/op
                 getUser·p0.9999: 29.491 ms/op
                 getUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247672
  mean =      3.876 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 429 
    [ 2.500,  5.000) = 234216 
    [ 5.000,  7.500) = 10877 
    [ 7.500, 10.000) = 1526 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.790 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     21.899 ms/op
     p(99.9900) =     28.723 ms/op
     p(99.9990) =     29.774 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.746 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 5.453 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.794 ±(99.9%) 0.017 ms/op
Iteration   1: 4.679 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.554 ms/op
                 listUser·p0.99:   8.893 ms/op
                 listUser·p0.999:  24.904 ms/op
                 listUser·p0.9999: 36.602 ms/op
                 listUser·p1.00:   37.224 ms/op

Iteration   2: 4.848 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   7.021 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  18.953 ms/op
                 listUser·p0.9999: 23.010 ms/op
                 listUser·p1.00:   26.542 ms/op

Iteration   3: 4.749 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.005 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   9.110 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201581
  mean =      4.757 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 162002 
    [ 5.000,  7.500) = 33011 
    [ 7.500, 10.000) = 5105 
    [10.000, 12.500) = 736 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.464 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.480 ms/op
     p(95.0000) =      6.611 ms/op
     p(99.0000) =      9.421 ms/op
     p(99.9000) =     22.099 ms/op
     p(99.9900) =     33.258 ms/op
     p(99.9990) =     37.158 ms/op
     p(99.9999) =     37.224 ms/op
    p(100.0000) =     37.224 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.044 ± 12.027  ops/ms
ClientPb.existUser                       thrpt       3   8.519 ±  2.937  ops/ms
ClientPb.getUser                         thrpt       3   8.162 ±  1.553  ops/ms
ClientPb.listUser                        thrpt       3   7.021 ±  1.612  ops/ms
ClientPb.createUser                       avgt       3   3.958 ±  0.891   ms/op
ClientPb.existUser                        avgt       3   3.651 ±  1.442   ms/op
ClientPb.getUser                          avgt       3   3.890 ±  1.388   ms/op
ClientPb.listUser                         avgt       3   4.707 ±  1.840   ms/op
ClientPb.createUser                     sample  246162   3.901 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.423            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.777            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.497            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.882            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.668            ms/op
ClientPb.createUser:createUser·p0.999   sample          22.741            ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.863            ms/op
ClientPb.createUser:createUser·p1.00    sample          33.391            ms/op
ClientPb.existUser                      sample  259600   3.697 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.116            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.580            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.071            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.407            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.463            ms/op
ClientPb.existUser:existUser·p0.999     sample          16.037            ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.869            ms/op
ClientPb.existUser:existUser·p1.00      sample          32.965            ms/op
ClientPb.getUser                        sample  247672   3.876 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.790            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.707            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.538            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.054            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.348            ms/op
ClientPb.getUser:getUser·p0.999         sample          21.899            ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.723            ms/op
ClientPb.getUser:getUser·p1.00          sample          30.081            ms/op
ClientPb.listUser                       sample  201581   4.757 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.464            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.481            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.480            ms/op
ClientPb.listUser:listUser·p0.95        sample           6.611            ms/op
ClientPb.listUser:listUser·p0.99        sample           9.421            ms/op
ClientPb.listUser:listUser·p0.999       sample          22.099            ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.258            ms/op
ClientPb.listUser:listUser·p1.00        sample          37.224            ms/op
