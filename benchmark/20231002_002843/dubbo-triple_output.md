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
# Warmup Iteration   1: 1.371 ops/ms
# Warmup Iteration   2: 2.878 ops/ms
# Warmup Iteration   3: 6.343 ops/ms
Iteration   1: 7.572 ops/ms
Iteration   2: 7.537 ops/ms
Iteration   3: 7.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.659 ±(99.9%) 3.317 ops/ms [Average]
  (min, avg, max) = (7.537, 7.659, 7.868), stdev = 0.182
  CI (99.9%): [4.342, 10.976] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.168 ops/ms
# Warmup Iteration   2: 5.903 ops/ms
# Warmup Iteration   3: 7.934 ops/ms
Iteration   1: 8.150 ops/ms
Iteration   2: 8.068 ops/ms
Iteration   3: 7.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.027 ±(99.9%) 2.680 ops/ms [Average]
  (min, avg, max) = (7.864, 8.027, 8.150), stdev = 0.147
  CI (99.9%): [5.347, 10.707] (assumes normal distribution)


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
# Warmup Iteration   1: 2.136 ops/ms
# Warmup Iteration   2: 6.088 ops/ms
# Warmup Iteration   3: 7.463 ops/ms
Iteration   1: 7.925 ops/ms
Iteration   2: 7.875 ops/ms
Iteration   3: 7.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.898 ±(99.9%) 0.461 ops/ms [Average]
  (min, avg, max) = (7.875, 7.898, 7.925), stdev = 0.025
  CI (99.9%): [7.438, 8.359] (assumes normal distribution)


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
# Warmup Iteration   1: 2.104 ops/ms
# Warmup Iteration   2: 5.892 ops/ms
# Warmup Iteration   3: 6.424 ops/ms
Iteration   1: 6.391 ops/ms
Iteration   2: 6.470 ops/ms
Iteration   3: 6.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.447 ±(99.9%) 0.906 ops/ms [Average]
  (min, avg, max) = (6.391, 6.447, 6.482), stdev = 0.050
  CI (99.9%): [5.542, 7.353] (assumes normal distribution)


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
# Warmup Iteration   1: 14.556 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.850 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.406 ±(99.9%) 0.008 ms/op
Iteration   1: 4.198 ±(99.9%) 0.006 ms/op
Iteration   2: 4.117 ±(99.9%) 0.004 ms/op
Iteration   3: 4.228 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.181 ±(99.9%) 1.049 ms/op [Average]
  (min, avg, max) = (4.117, 4.181, 4.228), stdev = 0.058
  CI (99.9%): [3.132, 5.230] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.842 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.167 ±(99.9%) 0.005 ms/op
Iteration   1: 4.033 ±(99.9%) 0.003 ms/op
Iteration   2: 3.982 ±(99.9%) 0.003 ms/op
Iteration   3: 3.923 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.979 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (3.923, 3.979, 4.033), stdev = 0.055
  CI (99.9%): [2.979, 4.980] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.731 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.729 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.003 ms/op
Iteration   1: 4.266 ±(99.9%) 0.006 ms/op
Iteration   2: 4.178 ±(99.9%) 0.004 ms/op
Iteration   3: 4.122 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.189 ±(99.9%) 1.328 ms/op [Average]
  (min, avg, max) = (4.122, 4.189, 4.266), stdev = 0.073
  CI (99.9%): [2.861, 5.516] (assumes normal distribution)


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
# Warmup Iteration   1: 16.890 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.881 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.001 ±(99.9%) 0.010 ms/op
Iteration   1: 4.936 ±(99.9%) 0.007 ms/op
Iteration   2: 4.898 ±(99.9%) 0.008 ms/op
Iteration   3: 4.806 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.880 ±(99.9%) 1.219 ms/op [Average]
  (min, avg, max) = (4.806, 4.880, 4.936), stdev = 0.067
  CI (99.9%): [3.661, 6.099] (assumes normal distribution)


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
# Warmup Iteration   1: 13.818 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 5.106 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.487 ±(99.9%) 0.021 ms/op
Iteration   1: 4.126 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   8.127 ms/op
                 createUser·p0.999:  23.724 ms/op
                 createUser·p0.9999: 26.157 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 4.102 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.210 ms/op
                 createUser·p0.99:   8.069 ms/op
                 createUser·p0.999:  17.016 ms/op
                 createUser·p0.9999: 28.751 ms/op
                 createUser·p1.00:   29.655 ms/op

Iteration   3: 4.236 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   8.897 ms/op
                 createUser·p0.999:  28.555 ms/op
                 createUser·p0.9999: 31.734 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 230993
  mean =      4.154 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 427 
    [ 2.500,  5.000) = 213015 
    [ 5.000,  7.500) = 13262 
    [ 7.500, 10.000) = 3279 
    [10.000, 12.500) = 440 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.501 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     24.412 ms/op
     p(99.9900) =     30.963 ms/op
     p(99.9990) =     32.412 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 13.350 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.597 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.014 ms/op
Iteration   1: 4.052 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.989 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   9.257 ms/op
                 existUser·p0.999:  13.192 ms/op
                 existUser·p0.9999: 23.607 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   2: 4.065 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.360 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   5.648 ms/op
                 existUser·p0.99:   8.815 ms/op
                 existUser·p0.999:  16.105 ms/op
                 existUser·p0.9999: 26.878 ms/op
                 existUser·p1.00:   30.048 ms/op

Iteration   3: 4.025 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.829 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   8.175 ms/op
                 existUser·p0.999:  23.854 ms/op
                 existUser·p0.9999: 31.162 ms/op
                 existUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 237241
  mean =      4.047 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 198 
    [ 2.500,  5.000) = 223020 
    [ 5.000,  7.500) = 8789 
    [ 7.500, 10.000) = 4226 
    [10.000, 12.500) = 618 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     16.105 ms/op
     p(99.9900) =     29.500 ms/op
     p(99.9990) =     31.314 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 14.475 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 4.828 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.013 ms/op
Iteration   1: 4.307 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.608 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   6.865 ms/op
                 getUser·p0.99:   8.962 ms/op
                 getUser·p0.999:  17.760 ms/op
                 getUser·p0.9999: 26.275 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   2: 4.136 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.376 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  25.375 ms/op
                 getUser·p0.9999: 28.508 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   3: 4.112 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   8.995 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 27.984 ms/op
                 getUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229359
  mean =      4.183 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 138 
    [ 2.500,  5.000) = 212948 
    [ 5.000,  7.500) = 10129 
    [ 7.500, 10.000) = 4894 
    [10.000, 12.500) = 744 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 133 

  Percentiles, ms/op:
      p(0.0000) =      1.376 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      8.864 ms/op
     p(99.9000) =     20.518 ms/op
     p(99.9900) =     27.890 ms/op
     p(99.9990) =     29.308 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 15.333 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.775 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.099 ±(99.9%) 0.019 ms/op
Iteration   1: 4.912 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   10.338 ms/op
                 listUser·p0.999:  22.509 ms/op
                 listUser·p0.9999: 25.182 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 4.921 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   4.702 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 29.131 ms/op
                 listUser·p1.00:   29.360 ms/op

Iteration   3: 5.002 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   11.026 ms/op
                 listUser·p0.999:  17.761 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 193999
  mean =      4.945 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 142802 
    [ 5.000,  7.500) = 43825 
    [ 7.500, 10.000) = 4773 
    [10.000, 12.500) = 1679 
    [12.500, 15.000) = 319 
    [15.000, 17.500) = 241 
    [17.500, 20.000) = 175 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.496 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     19.235 ms/op
     p(99.9900) =     26.647 ms/op
     p(99.9990) =     29.299 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.659 ± 3.317  ops/ms
ClientPb.existUser                       thrpt       3   8.027 ± 2.680  ops/ms
ClientPb.getUser                         thrpt       3   7.898 ± 0.461  ops/ms
ClientPb.listUser                        thrpt       3   6.447 ± 0.906  ops/ms
ClientPb.createUser                       avgt       3   4.181 ± 1.049   ms/op
ClientPb.existUser                        avgt       3   3.979 ± 1.001   ms/op
ClientPb.getUser                          avgt       3   4.189 ± 1.328   ms/op
ClientPb.listUser                         avgt       3   4.880 ± 1.219   ms/op
ClientPb.createUser                     sample  230993   4.154 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.501           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.339           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.412           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.963           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.768           ms/op
ClientPb.existUser                      sample  237241   4.047 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.360           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.897           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.105           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.244           ms/op
ClientPb.getUser                        sample  229359   4.183 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.376           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.620           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.864           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.518           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.890           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.327           ms/op
ClientPb.listUser                       sample  193999   4.945 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.496           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.486           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.235           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.647           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.360           ms/op
