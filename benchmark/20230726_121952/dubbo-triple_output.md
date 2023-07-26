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
# Warmup Iteration   1: 1.539 ops/ms
# Warmup Iteration   2: 3.282 ops/ms
# Warmup Iteration   3: 6.837 ops/ms
Iteration   1: 7.160 ops/ms
Iteration   2: 7.517 ops/ms
Iteration   3: 7.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.529 ±(99.9%) 6.860 ops/ms [Average]
  (min, avg, max) = (7.160, 7.529, 7.911), stdev = 0.376
  CI (99.9%): [0.669, 14.390] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.065 ops/ms
# Warmup Iteration   2: 7.000 ops/ms
# Warmup Iteration   3: 7.841 ops/ms
Iteration   1: 8.025 ops/ms
Iteration   2: 8.209 ops/ms
Iteration   3: 8.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.180 ±(99.9%) 2.608 ops/ms [Average]
  (min, avg, max) = (8.025, 8.180, 8.306), stdev = 0.143
  CI (99.9%): [5.572, 10.787] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 6.271 ops/ms
# Warmup Iteration   3: 7.708 ops/ms
Iteration   1: 7.655 ops/ms
Iteration   2: 8.152 ops/ms
Iteration   3: 7.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.897 ±(99.9%) 4.533 ops/ms [Average]
  (min, avg, max) = (7.655, 7.897, 8.152), stdev = 0.248
  CI (99.9%): [3.364, 12.431] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.101 ops/ms
# Warmup Iteration   2: 5.512 ops/ms
# Warmup Iteration   3: 6.266 ops/ms
Iteration   1: 6.712 ops/ms
Iteration   2: 6.711 ops/ms
Iteration   3: 6.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.733 ±(99.9%) 0.690 ops/ms [Average]
  (min, avg, max) = (6.711, 6.733, 6.777), stdev = 0.038
  CI (99.9%): [6.043, 7.424] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.929 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.276 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.355 ±(99.9%) 0.009 ms/op
Iteration   1: 4.152 ±(99.9%) 0.006 ms/op
Iteration   2: 4.176 ±(99.9%) 0.009 ms/op
Iteration   3: 3.969 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.099 ±(99.9%) 2.063 ms/op [Average]
  (min, avg, max) = (3.969, 4.099, 4.176), stdev = 0.113
  CI (99.9%): [2.037, 6.162] (assumes normal distribution)


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
# Warmup Iteration   1: 11.819 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.335 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.013 ms/op
Iteration   1: 3.973 ±(99.9%) 0.008 ms/op
Iteration   2: 3.916 ±(99.9%) 0.007 ms/op
Iteration   3: 3.819 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.903 ±(99.9%) 1.425 ms/op [Average]
  (min, avg, max) = (3.819, 3.903, 3.973), stdev = 0.078
  CI (99.9%): [2.478, 5.328] (assumes normal distribution)


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
# Warmup Iteration   1: 13.436 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.491 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.005 ms/op
Iteration   1: 4.279 ±(99.9%) 0.005 ms/op
Iteration   2: 4.077 ±(99.9%) 0.009 ms/op
Iteration   3: 3.897 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.084 ±(99.9%) 3.493 ms/op [Average]
  (min, avg, max) = (3.897, 4.084, 4.279), stdev = 0.191
  CI (99.9%): [0.591, 7.577] (assumes normal distribution)


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
# Warmup Iteration   1: 13.861 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.423 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.796 ±(99.9%) 0.008 ms/op
Iteration   1: 4.943 ±(99.9%) 0.005 ms/op
Iteration   2: 4.869 ±(99.9%) 0.008 ms/op
Iteration   3: 4.645 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.819 ±(99.9%) 2.827 ms/op [Average]
  (min, avg, max) = (4.645, 4.819, 4.943), stdev = 0.155
  CI (99.9%): [1.992, 7.646] (assumes normal distribution)


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
# Warmup Iteration   1: 12.600 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 5.574 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.668 ±(99.9%) 0.021 ms/op
Iteration   1: 4.040 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.118 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   7.231 ms/op
                 createUser·p0.999:  25.100 ms/op
                 createUser·p0.9999: 27.951 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   2: 4.095 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.201 ms/op
                 createUser·p0.999:  11.075 ms/op
                 createUser·p0.9999: 29.189 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   3: 3.961 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.778 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  29.670 ms/op
                 createUser·p0.9999: 35.833 ms/op
                 createUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237957
  mean =      4.032 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 194 
    [ 2.500,  5.000) = 225991 
    [ 5.000,  7.500) = 9809 
    [ 7.500, 10.000) = 1398 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     25.166 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     36.257 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.790 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.369 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.014 ms/op
Iteration   1: 3.986 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.876 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   5.053 ms/op
                 existUser·p0.99:   7.045 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 27.489 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   2: 3.942 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.970 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   8.389 ms/op
                 existUser·p0.999:  24.740 ms/op
                 existUser·p0.9999: 31.585 ms/op
                 existUser·p1.00:   31.752 ms/op

Iteration   3: 3.845 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   6.845 ms/op
                 existUser·p0.999:  13.365 ms/op
                 existUser·p0.9999: 29.809 ms/op
                 existUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244506
  mean =      3.924 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 207 
    [ 2.500,  5.000) = 233134 
    [ 5.000,  7.500) = 8757 
    [ 7.500, 10.000) = 1929 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     30.758 ms/op
     p(99.9990) =     31.719 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 12.835 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 5.614 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.397 ±(99.9%) 0.015 ms/op
Iteration   1: 4.095 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.907 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  17.294 ms/op
                 getUser·p0.9999: 24.183 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 4.146 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.913 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   7.692 ms/op
                 getUser·p0.999:  23.154 ms/op
                 getUser·p0.9999: 30.245 ms/op
                 getUser·p1.00:   31.621 ms/op

Iteration   3: 4.081 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   8.086 ms/op
                 getUser·p0.999:  12.206 ms/op
                 getUser·p0.9999: 27.623 ms/op
                 getUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233585
  mean =      4.107 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 219051 
    [ 5.000,  7.500) = 11251 
    [ 7.500, 10.000) = 2569 
    [10.000, 12.500) = 365 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     19.707 ms/op
     p(99.9900) =     29.053 ms/op
     p(99.9990) =     31.303 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 14.557 ±(99.9%) 0.224 ms/op
# Warmup Iteration   2: 5.525 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.888 ±(99.9%) 0.019 ms/op
Iteration   1: 4.747 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.786 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  26.949 ms/op
                 listUser·p0.9999: 30.000 ms/op
                 listUser·p1.00:   32.670 ms/op

Iteration   2: 4.918 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  18.481 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   3: 4.841 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.781 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  16.808 ms/op
                 listUser·p0.9999: 21.214 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198338
  mean =      4.834 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 153724 
    [ 5.000,  7.500) = 39846 
    [ 7.500, 10.000) = 3744 
    [10.000, 12.500) = 482 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.011 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     20.982 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     30.865 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.529 ± 6.860  ops/ms
ClientPb.existUser                       thrpt       3   8.180 ± 2.608  ops/ms
ClientPb.getUser                         thrpt       3   7.897 ± 4.533  ops/ms
ClientPb.listUser                        thrpt       3   6.733 ± 0.690  ops/ms
ClientPb.createUser                       avgt       3   4.099 ± 2.063   ms/op
ClientPb.existUser                        avgt       3   3.903 ± 1.425   ms/op
ClientPb.getUser                          avgt       3   4.084 ± 3.493   ms/op
ClientPb.listUser                         avgt       3   4.819 ± 2.827   ms/op
ClientPb.createUser                     sample  237957   4.032 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.356           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.176           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.166           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.603           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.438           ms/op
ClientPb.existUser                      sample  244506   3.924 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.575           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.463           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.337           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.758           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.752           ms/op
ClientPb.getUser                        sample  233585   4.107 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.958           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.604           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.259           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.135           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.707           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.053           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.621           ms/op
ClientPb.listUser                       sample  198338   4.834 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.011           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.046           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.982           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.803           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.670           ms/op
