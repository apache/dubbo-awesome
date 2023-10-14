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
# Warmup Iteration   1: 1.116 ops/ms
# Warmup Iteration   2: 2.500 ops/ms
# Warmup Iteration   3: 5.610 ops/ms
Iteration   1: 5.986 ops/ms
Iteration   2: 6.102 ops/ms
Iteration   3: 6.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.105 ±(99.9%) 2.194 ops/ms [Average]
  (min, avg, max) = (5.986, 6.105, 6.226), stdev = 0.120
  CI (99.9%): [3.910, 8.299] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.681 ops/ms
# Warmup Iteration   2: 5.587 ops/ms
# Warmup Iteration   3: 6.319 ops/ms
Iteration   1: 6.372 ops/ms
Iteration   2: 6.324 ops/ms
Iteration   3: 6.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.418 ±(99.9%) 2.234 ops/ms [Average]
  (min, avg, max) = (6.324, 6.418, 6.556), stdev = 0.122
  CI (99.9%): [4.184, 8.651] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.604 ops/ms
# Warmup Iteration   2: 4.646 ops/ms
# Warmup Iteration   3: 5.929 ops/ms
Iteration   1: 5.849 ops/ms
Iteration   2: 5.928 ops/ms
Iteration   3: 6.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.018 ±(99.9%) 4.152 ops/ms [Average]
  (min, avg, max) = (5.849, 6.018, 6.276), stdev = 0.228
  CI (99.9%): [1.865, 10.170] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.581 ops/ms
# Warmup Iteration   2: 3.964 ops/ms
# Warmup Iteration   3: 5.144 ops/ms
Iteration   1: 5.036 ops/ms
Iteration   2: 5.271 ops/ms
Iteration   3: 5.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.175 ±(99.9%) 2.257 ops/ms [Average]
  (min, avg, max) = (5.036, 5.175, 5.271), stdev = 0.124
  CI (99.9%): [2.918, 7.432] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 15.904 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 6.190 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.681 ±(99.9%) 0.010 ms/op
Iteration   1: 5.382 ±(99.9%) 0.009 ms/op
Iteration   2: 5.311 ±(99.9%) 0.011 ms/op
Iteration   3: 5.318 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.337 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (5.311, 5.337, 5.382), stdev = 0.039
  CI (99.9%): [4.624, 6.049] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.140 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.132 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.146 ±(99.9%) 0.010 ms/op
Iteration   1: 5.051 ±(99.9%) 0.010 ms/op
Iteration   2: 5.173 ±(99.9%) 0.007 ms/op
Iteration   3: 5.161 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.128 ±(99.9%) 1.226 ms/op [Average]
  (min, avg, max) = (5.051, 5.128, 5.173), stdev = 0.067
  CI (99.9%): [3.902, 6.355] (assumes normal distribution)


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
# Warmup Iteration   1: 16.079 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 6.105 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.400 ±(99.9%) 0.011 ms/op
Iteration   1: 5.479 ±(99.9%) 0.013 ms/op
Iteration   2: 5.116 ±(99.9%) 0.015 ms/op
Iteration   3: 5.295 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.297 ±(99.9%) 3.309 ms/op [Average]
  (min, avg, max) = (5.116, 5.297, 5.479), stdev = 0.181
  CI (99.9%): [1.988, 8.605] (assumes normal distribution)


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
# Warmup Iteration   1: 19.320 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.222 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.170 ±(99.9%) 0.014 ms/op
Iteration   1: 6.130 ±(99.9%) 0.011 ms/op
Iteration   2: 6.270 ±(99.9%) 0.012 ms/op
Iteration   3: 6.088 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.163 ±(99.9%) 1.738 ms/op [Average]
  (min, avg, max) = (6.088, 6.163, 6.270), stdev = 0.095
  CI (99.9%): [4.425, 7.901] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.771 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 6.581 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.801 ±(99.9%) 0.031 ms/op
Iteration   1: 5.319 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.408 ms/op
                 createUser·p0.50:   4.964 ms/op
                 createUser·p0.90:   6.611 ms/op
                 createUser·p0.95:   7.922 ms/op
                 createUser·p0.99:   10.630 ms/op
                 createUser·p0.999:  24.572 ms/op
                 createUser·p0.9999: 42.789 ms/op
                 createUser·p1.00:   44.564 ms/op

Iteration   2: 5.292 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   4.973 ms/op
                 createUser·p0.90:   6.455 ms/op
                 createUser·p0.95:   7.586 ms/op
                 createUser·p0.99:   10.469 ms/op
                 createUser·p0.999:  25.521 ms/op
                 createUser·p0.9999: 42.657 ms/op
                 createUser·p1.00:   44.630 ms/op

Iteration   3: 5.399 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.009 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.619 ms/op
                 createUser·p0.95:   7.643 ms/op
                 createUser·p0.99:   11.227 ms/op
                 createUser·p0.999:  29.900 ms/op
                 createUser·p0.9999: 33.953 ms/op
                 createUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179652
  mean =      5.336 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 89486 
    [ 5.000, 10.000) = 87843 
    [10.000, 15.000) = 1753 
    [15.000, 20.000) = 209 
    [20.000, 25.000) = 159 
    [25.000, 30.000) = 88 
    [30.000, 35.000) = 73 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.990 ms/op
     p(50.0000) =      5.005 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =      7.741 ms/op
     p(99.0000) =     10.699 ms/op
     p(99.9000) =     25.821 ms/op
     p(99.9900) =     40.766 ms/op
     p(99.9990) =     44.578 ms/op
     p(99.9999) =     44.630 ms/op
    p(100.0000) =     44.630 ms/op


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
# Warmup Iteration   1: 16.621 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.040 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.232 ±(99.9%) 0.021 ms/op
Iteration   1: 5.299 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   4.858 ms/op
                 existUser·p0.90:   6.963 ms/op
                 existUser·p0.95:   8.200 ms/op
                 existUser·p0.99:   12.026 ms/op
                 existUser·p0.999:  23.233 ms/op
                 existUser·p0.9999: 27.590 ms/op
                 existUser·p1.00:   31.719 ms/op

Iteration   2: 5.099 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.183 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   6.193 ms/op
                 existUser·p0.95:   7.709 ms/op
                 existUser·p0.99:   11.190 ms/op
                 existUser·p0.999:  25.145 ms/op
                 existUser·p0.9999: 28.041 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   3: 5.106 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.101 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.103 ms/op
                 existUser·p0.95:   7.266 ms/op
                 existUser·p0.99:   11.059 ms/op
                 existUser·p0.999:  26.378 ms/op
                 existUser·p0.9999: 29.109 ms/op
                 existUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185615
  mean =      5.166 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 113075 
    [ 5.000,  7.500) = 61610 
    [ 7.500, 10.000) = 7578 
    [10.000, 12.500) = 2040 
    [12.500, 15.000) = 823 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.837 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.832 ms/op
     p(99.0000) =     11.452 ms/op
     p(99.9000) =     23.507 ms/op
     p(99.9900) =     28.391 ms/op
     p(99.9990) =     31.551 ms/op
     p(99.9999) =     31.719 ms/op
    p(100.0000) =     31.719 ms/op


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
# Warmup Iteration   1: 16.941 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.467 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.527 ±(99.9%) 0.020 ms/op
Iteration   1: 5.444 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.200 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.734 ms/op
                 getUser·p0.95:   8.167 ms/op
                 getUser·p0.99:   11.911 ms/op
                 getUser·p0.999:  26.083 ms/op
                 getUser·p0.9999: 30.409 ms/op
                 getUser·p1.00:   30.474 ms/op

Iteration   2: 5.286 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.265 ms/op
                 getUser·p0.50:   4.989 ms/op
                 getUser·p0.90:   6.513 ms/op
                 getUser·p0.95:   7.815 ms/op
                 getUser·p0.99:   9.798 ms/op
                 getUser·p0.999:  23.954 ms/op
                 getUser·p0.9999: 28.441 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   3: 5.321 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.946 ms/op
                 getUser·p0.50:   4.964 ms/op
                 getUser·p0.90:   6.611 ms/op
                 getUser·p0.95:   7.881 ms/op
                 getUser·p0.99:   11.289 ms/op
                 getUser·p0.999:  25.290 ms/op
                 getUser·p0.9999: 29.490 ms/op
                 getUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 179310
  mean =      5.349 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 87931 
    [ 5.000,  7.500) = 79524 
    [ 7.500, 10.000) = 9253 
    [10.000, 12.500) = 1499 
    [12.500, 15.000) = 602 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.946 ms/op
     p(50.0000) =      5.022 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.946 ms/op
     p(99.0000) =     10.977 ms/op
     p(99.9000) =     25.080 ms/op
     p(99.9900) =     29.950 ms/op
     p(99.9990) =     30.474 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 19.681 ±(99.9%) 0.328 ms/op
# Warmup Iteration   2: 7.811 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.237 ±(99.9%) 0.029 ms/op
Iteration   1: 6.273 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   5.808 ms/op
                 listUser·p0.90:   7.946 ms/op
                 listUser·p0.95:   9.257 ms/op
                 listUser·p0.99:   12.222 ms/op
                 listUser·p0.999:  23.791 ms/op
                 listUser·p0.9999: 26.310 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 6.228 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.077 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   7.684 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   12.444 ms/op
                 listUser·p0.999:  26.662 ms/op
                 listUser·p0.9999: 30.463 ms/op
                 listUser·p1.00:   31.457 ms/op

Iteration   3: 6.371 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.046 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   8.096 ms/op
                 listUser·p0.95:   9.470 ms/op
                 listUser·p0.99:   11.846 ms/op
                 listUser·p0.999:  26.102 ms/op
                 listUser·p0.9999: 29.914 ms/op
                 listUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152521
  mean =      6.290 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 10667 
    [ 5.000,  7.500) = 123197 
    [ 7.500, 10.000) = 13924 
    [10.000, 12.500) = 3455 
    [12.500, 15.000) = 522 
    [15.000, 17.500) = 313 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 116 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      5.874 ms/op
     p(90.0000) =      7.864 ms/op
     p(95.0000) =      9.241 ms/op
     p(99.0000) =     12.009 ms/op
     p(99.9000) =     25.297 ms/op
     p(99.9900) =     29.876 ms/op
     p(99.9990) =     31.440 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.105 ± 2.194  ops/ms
ClientPb.existUser                       thrpt       3   6.418 ± 2.234  ops/ms
ClientPb.getUser                         thrpt       3   6.018 ± 4.152  ops/ms
ClientPb.listUser                        thrpt       3   5.175 ± 2.257  ops/ms
ClientPb.createUser                       avgt       3   5.337 ± 0.712   ms/op
ClientPb.existUser                        avgt       3   5.128 ± 1.226   ms/op
ClientPb.getUser                          avgt       3   5.297 ± 3.309   ms/op
ClientPb.listUser                         avgt       3   6.163 ± 1.738   ms/op
ClientPb.createUser                     sample  179652   5.336 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.990           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.005           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.562           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.741           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.699           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.821           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.766           ms/op
ClientPb.createUser:createUser·p1.00    sample          44.630           ms/op
ClientPb.existUser                      sample  185615   5.166 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.837           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.825           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.373           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.832           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.452           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.507           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.391           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.719           ms/op
ClientPb.getUser                        sample  179310   5.349 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.946           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.022           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.946           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.977           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.080           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.950           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.474           ms/op
ClientPb.listUser                       sample  152521   6.290 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.862           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.874           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.864           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.241           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.009           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.297           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.876           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.457           ms/op
