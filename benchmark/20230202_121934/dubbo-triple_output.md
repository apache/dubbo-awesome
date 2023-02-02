# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.618 ops/ms
# Warmup Iteration   2: 3.193 ops/ms
# Warmup Iteration   3: 6.895 ops/ms
Iteration   1: 7.476 ops/ms
Iteration   2: 8.048 ops/ms
Iteration   3: 8.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.878 ±(99.9%) 6.383 ops/ms [Average]
  (min, avg, max) = (7.476, 7.878, 8.111), stdev = 0.350
  CI (99.9%): [1.495, 14.262] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.353 ops/ms
# Warmup Iteration   2: 6.842 ops/ms
# Warmup Iteration   3: 8.175 ops/ms
Iteration   1: 8.345 ops/ms
Iteration   2: 8.650 ops/ms
Iteration   3: 8.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.490 ±(99.9%) 2.799 ops/ms [Average]
  (min, avg, max) = (8.345, 8.490, 8.650), stdev = 0.153
  CI (99.9%): [5.691, 11.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.228 ops/ms
# Warmup Iteration   2: 6.362 ops/ms
# Warmup Iteration   3: 7.926 ops/ms
Iteration   1: 8.095 ops/ms
Iteration   2: 7.934 ops/ms
Iteration   3: 8.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.045 ±(99.9%) 1.741 ops/ms [Average]
  (min, avg, max) = (7.934, 8.045, 8.104), stdev = 0.095
  CI (99.9%): [6.303, 9.786] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.425 ops/ms
# Warmup Iteration   2: 5.279 ops/ms
# Warmup Iteration   3: 6.565 ops/ms
Iteration   1: 6.624 ops/ms
Iteration   2: 6.689 ops/ms
Iteration   3: 6.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.750 ±(99.9%) 3.010 ops/ms [Average]
  (min, avg, max) = (6.624, 6.750, 6.936), stdev = 0.165
  CI (99.9%): [3.740, 9.760] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.693 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.726 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.264 ±(99.9%) 0.011 ms/op
Iteration   1: 4.088 ±(99.9%) 0.013 ms/op
Iteration   2: 3.873 ±(99.9%) 0.008 ms/op
Iteration   3: 3.950 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.970 ±(99.9%) 1.991 ms/op [Average]
  (min, avg, max) = (3.873, 3.970, 4.088), stdev = 0.109
  CI (99.9%): [1.979, 5.961] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.221 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.322 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.004 ms/op
Iteration   1: 3.851 ±(99.9%) 0.005 ms/op
Iteration   2: 3.754 ±(99.9%) 0.007 ms/op
Iteration   3: 3.686 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.764 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (3.686, 3.764, 3.851), stdev = 0.083
  CI (99.9%): [2.243, 5.284] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.595 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.041 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.324 ±(99.9%) 0.004 ms/op
Iteration   1: 4.102 ±(99.9%) 0.006 ms/op
Iteration   2: 4.001 ±(99.9%) 0.007 ms/op
Iteration   3: 3.980 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.028 ±(99.9%) 1.190 ms/op [Average]
  (min, avg, max) = (3.980, 4.028, 4.102), stdev = 0.065
  CI (99.9%): [2.838, 5.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.137 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.228 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.809 ±(99.9%) 0.012 ms/op
Iteration   1: 4.759 ±(99.9%) 0.010 ms/op
Iteration   2: 4.643 ±(99.9%) 0.011 ms/op
Iteration   3: 4.608 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.670 ±(99.9%) 1.438 ms/op [Average]
  (min, avg, max) = (4.608, 4.670, 4.759), stdev = 0.079
  CI (99.9%): [3.232, 6.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.213 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.021 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.490 ±(99.9%) 0.021 ms/op
Iteration   1: 4.059 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.872 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.186 ms/op
                 createUser·p0.99:   7.373 ms/op
                 createUser·p0.999:  25.573 ms/op
                 createUser·p0.9999: 30.904 ms/op
                 createUser·p1.00:   31.359 ms/op

Iteration   2: 4.018 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.009 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  10.820 ms/op
                 createUser·p0.9999: 31.491 ms/op
                 createUser·p1.00:   32.506 ms/op

Iteration   3: 3.957 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.956 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   7.315 ms/op
                 createUser·p0.999:  27.664 ms/op
                 createUser·p0.9999: 30.605 ms/op
                 createUser·p1.00:   32.866 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239130
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 226 
    [ 2.500,  5.000) = 226427 
    [ 5.000,  7.500) = 10582 
    [ 7.500, 10.000) = 1181 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 126 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.872 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     25.555 ms/op
     p(99.9900) =     30.966 ms/op
     p(99.9990) =     32.480 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 12.095 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.013 ms/op
Iteration   1: 4.039 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  12.554 ms/op
                 existUser·p0.9999: 26.020 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   2: 3.795 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.504 ms/op
                 existUser·p0.999:  23.307 ms/op
                 existUser·p0.9999: 28.602 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   3: 3.844 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   2.056 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  14.917 ms/op
                 existUser·p0.9999: 27.187 ms/op
                 existUser·p1.00:   27.656 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246789
  mean =      3.890 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 292 
    [ 2.500,  5.000) = 234014 
    [ 5.000,  7.500) = 10943 
    [ 7.500, 10.000) = 1012 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 105 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     14.756 ms/op
     p(99.9900) =     27.437 ms/op
     p(99.9990) =     29.353 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.141 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 4.652 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.305 ±(99.9%) 0.017 ms/op
Iteration   1: 3.908 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.497 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   7.504 ms/op
                 getUser·p0.999:  13.448 ms/op
                 getUser·p0.9999: 23.503 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 3.979 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.048 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.111 ms/op
                 getUser·p0.99:   7.381 ms/op
                 getUser·p0.999:  11.791 ms/op
                 getUser·p0.9999: 27.000 ms/op
                 getUser·p1.00:   27.656 ms/op

Iteration   3: 3.808 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.862 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  25.788 ms/op
                 getUser·p0.9999: 28.449 ms/op
                 getUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246252
  mean =      3.897 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 118 
    [ 2.500,  5.000) = 236434 
    [ 5.000,  7.500) = 7886 
    [ 7.500, 10.000) = 1191 
    [10.000, 12.500) = 355 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 103 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     27.537 ms/op
     p(99.9990) =     29.622 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.542 ±(99.9%) 0.221 ms/op
# Warmup Iteration   2: 5.863 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.900 ±(99.9%) 0.017 ms/op
Iteration   1: 4.808 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.595 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  25.292 ms/op
                 listUser·p0.9999: 27.733 ms/op
                 listUser·p1.00:   29.196 ms/op

Iteration   2: 4.759 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.593 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  20.404 ms/op
                 listUser·p0.9999: 27.001 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   3: 4.735 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.544 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  16.252 ms/op
                 listUser·p0.9999: 21.275 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201144
  mean =      4.767 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 165855 
    [ 5.000,  7.500) = 31419 
    [ 7.500, 10.000) = 2722 
    [10.000, 12.500) = 520 
    [12.500, 15.000) = 161 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 100 

  Percentiles, ms/op:
      p(0.0000) =      1.595 ms/op
     p(50.0000) =      4.612 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     28.474 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.878 ± 6.383  ops/ms
ClientPb.existUser                       thrpt       3   8.490 ± 2.799  ops/ms
ClientPb.getUser                         thrpt       3   8.045 ± 1.741  ops/ms
ClientPb.listUser                        thrpt       3   6.750 ± 3.010  ops/ms
ClientPb.createUser                       avgt       3   3.970 ± 1.991   ms/op
ClientPb.existUser                        avgt       3   3.764 ± 1.521   ms/op
ClientPb.getUser                          avgt       3   4.028 ± 1.190   ms/op
ClientPb.listUser                         avgt       3   4.670 ± 1.438   ms/op
ClientPb.createUser                     sample  239130   4.011 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.872           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.152           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.555           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.966           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.866           ms/op
ClientPb.existUser                      sample  246789   3.890 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.483           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.756           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.437           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.491           ms/op
ClientPb.getUser                        sample  246252   3.897 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.497           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.792           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.988           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.287           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.537           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.688           ms/op
ClientPb.listUser                       sample  201144   4.767 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.595           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.612           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.011           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.266           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.296           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.196           ms/op
