# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.680 ops/ms
# Warmup Iteration   2: 3.977 ops/ms
# Warmup Iteration   3: 7.233 ops/ms
Iteration   1: 7.500 ops/ms
Iteration   2: 7.909 ops/ms
Iteration   3: 7.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.723 ±(99.9%) 3.780 ops/ms [Average]
  (min, avg, max) = (7.500, 7.723, 7.909), stdev = 0.207
  CI (99.9%): [3.944, 11.503] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.130 ops/ms
# Warmup Iteration   2: 6.988 ops/ms
# Warmup Iteration   3: 7.939 ops/ms
Iteration   1: 8.262 ops/ms
Iteration   2: 8.238 ops/ms
Iteration   3: 8.214 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.238 ±(99.9%) 0.440 ops/ms [Average]
  (min, avg, max) = (8.214, 8.238, 8.262), stdev = 0.024
  CI (99.9%): [7.798, 8.678] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.969 ops/ms
# Warmup Iteration   2: 6.003 ops/ms
# Warmup Iteration   3: 7.675 ops/ms
Iteration   1: 7.621 ops/ms
Iteration   2: 7.646 ops/ms
Iteration   3: 7.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.647 ±(99.9%) 0.506 ops/ms [Average]
  (min, avg, max) = (7.621, 7.647, 7.676), stdev = 0.028
  CI (99.9%): [7.142, 8.153] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.022 ops/ms
# Warmup Iteration   2: 5.186 ops/ms
# Warmup Iteration   3: 6.385 ops/ms
Iteration   1: 6.553 ops/ms
Iteration   2: 6.819 ops/ms
Iteration   3: 6.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.692 ±(99.9%) 2.436 ops/ms [Average]
  (min, avg, max) = (6.553, 6.692, 6.819), stdev = 0.134
  CI (99.9%): [4.256, 9.128] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 15.325 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.710 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.354 ±(99.9%) 0.006 ms/op
Iteration   1: 4.058 ±(99.9%) 0.004 ms/op
Iteration   2: 4.234 ±(99.9%) 0.004 ms/op
Iteration   3: 4.201 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.165 ±(99.9%) 1.708 ms/op [Average]
  (min, avg, max) = (4.058, 4.165, 4.234), stdev = 0.094
  CI (99.9%): [2.456, 5.873] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.226 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.443 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.003 ms/op
Iteration   1: 3.814 ±(99.9%) 0.007 ms/op
Iteration   2: 3.984 ±(99.9%) 0.004 ms/op
Iteration   3: 4.199 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.999 ±(99.9%) 3.516 ms/op [Average]
  (min, avg, max) = (3.814, 3.999, 4.199), stdev = 0.193
  CI (99.9%): [0.483, 7.515] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.804 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.694 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.643 ±(99.9%) 0.005 ms/op
Iteration   1: 4.225 ±(99.9%) 0.005 ms/op
Iteration   2: 4.046 ±(99.9%) 0.009 ms/op
Iteration   3: 3.997 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.089 ±(99.9%) 2.184 ms/op [Average]
  (min, avg, max) = (3.997, 4.089, 4.225), stdev = 0.120
  CI (99.9%): [1.905, 6.274] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.372 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.387 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.807 ±(99.9%) 0.006 ms/op
Iteration   1: 4.791 ±(99.9%) 0.005 ms/op
Iteration   2: 4.740 ±(99.9%) 0.006 ms/op
Iteration   3: 4.747 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.759 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (4.740, 4.759, 4.791), stdev = 0.027
  CI (99.9%): [4.262, 5.256] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.396 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 5.086 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.469 ±(99.9%) 0.018 ms/op
Iteration   1: 3.981 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   2.054 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   7.513 ms/op
                 createUser·p0.999:  24.825 ms/op
                 createUser·p0.9999: 36.176 ms/op
                 createUser·p1.00:   46.334 ms/op

Iteration   2: 4.042 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   7.324 ms/op
                 createUser·p0.999:  11.796 ms/op
                 createUser·p0.9999: 34.019 ms/op
                 createUser·p1.00:   34.275 ms/op

Iteration   3: 4.082 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.938 ms/op
                 createUser·p0.999:  29.065 ms/op
                 createUser·p0.9999: 31.463 ms/op
                 createUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237769
  mean =      4.035 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 225691 
    [ 5.000, 10.000) = 11170 
    [10.000, 15.000) = 542 
    [15.000, 20.000) = 54 
    [20.000, 25.000) = 83 
    [25.000, 30.000) = 139 
    [30.000, 35.000) = 79 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     24.871 ms/op
     p(99.9900) =     34.013 ms/op
     p(99.9990) =     36.307 ms/op
     p(99.9999) =     46.334 ms/op
    p(100.0000) =     46.334 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 11.954 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.276 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.013 ms/op
Iteration   1: 3.892 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.866 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   7.619 ms/op
                 existUser·p0.999:  20.868 ms/op
                 existUser·p0.9999: 23.717 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   2: 3.920 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.769 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.751 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  13.354 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 3.817 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.953 ms/op
                 existUser·p0.999:  23.948 ms/op
                 existUser·p0.9999: 27.152 ms/op
                 existUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247508
  mean =      3.876 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 358 
    [ 2.500,  5.000) = 238444 
    [ 5.000,  7.500) = 6761 
    [ 7.500, 10.000) = 1194 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 109 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     20.758 ms/op
     p(99.9900) =     27.206 ms/op
     p(99.9990) =     28.039 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.049 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 5.018 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.422 ±(99.9%) 0.016 ms/op
Iteration   1: 4.166 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.425 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   9.126 ms/op
                 getUser·p0.999:  20.291 ms/op
                 getUser·p0.9999: 24.619 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   2: 3.989 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.097 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  12.117 ms/op
                 getUser·p0.9999: 26.215 ms/op
                 getUser·p1.00:   37.028 ms/op

Iteration   3: 3.921 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.614 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  11.803 ms/op
                 getUser·p0.9999: 26.897 ms/op
                 getUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238260
  mean =      4.023 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 224741 
    [ 5.000,  7.500) = 10376 
    [ 7.500, 10.000) = 2178 
    [10.000, 12.500) = 502 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 93 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      7.963 ms/op
     p(99.9000) =     15.950 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     27.225 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.443 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.460 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.871 ±(99.9%) 0.016 ms/op
Iteration   1: 4.858 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  25.100 ms/op
                 listUser·p0.9999: 28.097 ms/op
                 listUser·p1.00:   29.491 ms/op

Iteration   2: 4.677 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.911 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   8.863 ms/op
                 listUser·p0.999:  17.259 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 4.676 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  16.050 ms/op
                 listUser·p0.9999: 18.940 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202603
  mean =      4.736 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 169148 
    [ 5.000,  7.500) = 29332 
    [ 7.500, 10.000) = 2915 
    [10.000, 12.500) = 473 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 222 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.561 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     19.510 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     29.098 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.723 ± 3.780  ops/ms
ClientPb.existUser                       thrpt       3   8.238 ± 0.440  ops/ms
ClientPb.getUser                         thrpt       3   7.647 ± 0.506  ops/ms
ClientPb.listUser                        thrpt       3   6.692 ± 2.436  ops/ms
ClientPb.createUser                       avgt       3   4.165 ± 1.708   ms/op
ClientPb.existUser                        avgt       3   3.999 ± 3.516   ms/op
ClientPb.getUser                          avgt       3   4.089 ± 2.184   ms/op
ClientPb.listUser                         avgt       3   4.759 ± 0.497   ms/op
ClientPb.createUser                     sample  237769   4.035 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.493           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.619           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.871           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.013           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.334           ms/op
ClientPb.existUser                      sample  247508   3.876 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.524           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.021           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.758           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.206           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.213           ms/op
ClientPb.getUser                        sample  238260   4.023 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.425           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.095           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.963           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.950           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.247           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.028           ms/op
ClientPb.listUser                       sample  202603   4.736 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.421           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.169           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.561           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.749           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.510           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.903           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.491           ms/op
