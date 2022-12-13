# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.164 ops/ms
# Warmup Iteration   2: 3.143 ops/ms
# Warmup Iteration   3: 5.806 ops/ms
Iteration   1: 5.714 ops/ms
Iteration   2: 6.142 ops/ms
Iteration   3: 5.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.828 ±(99.9%) 5.033 ops/ms [Average]
  (min, avg, max) = (5.627, 5.828, 6.142), stdev = 0.276
  CI (99.9%): [0.795, 10.861] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 1.598 ops/ms
# Warmup Iteration   2: 5.367 ops/ms
# Warmup Iteration   3: 6.581 ops/ms
Iteration   1: 6.801 ops/ms
Iteration   2: 6.744 ops/ms
Iteration   3: 6.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.693 ±(99.9%) 2.568 ops/ms [Average]
  (min, avg, max) = (6.534, 6.693, 6.801), stdev = 0.141
  CI (99.9%): [4.125, 9.261] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.634 ops/ms
# Warmup Iteration   2: 4.974 ops/ms
# Warmup Iteration   3: 6.208 ops/ms
Iteration   1: 6.308 ops/ms
Iteration   2: 6.325 ops/ms
Iteration   3: 6.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.233 ±(99.9%) 2.638 ops/ms [Average]
  (min, avg, max) = (6.066, 6.233, 6.325), stdev = 0.145
  CI (99.9%): [3.595, 8.871] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.620 ops/ms
# Warmup Iteration   2: 3.984 ops/ms
# Warmup Iteration   3: 5.422 ops/ms
Iteration   1: 5.302 ops/ms
Iteration   2: 5.276 ops/ms
Iteration   3: 5.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.416 ±(99.9%) 4.012 ops/ms [Average]
  (min, avg, max) = (5.276, 5.416, 5.669), stdev = 0.220
  CI (99.9%): [1.404, 9.428] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 19.565 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 6.234 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.503 ±(99.9%) 0.009 ms/op
Iteration   1: 5.239 ±(99.9%) 0.014 ms/op
Iteration   2: 5.441 ±(99.9%) 0.010 ms/op
Iteration   3: 5.368 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.349 ±(99.9%) 1.868 ms/op [Average]
  (min, avg, max) = (5.239, 5.349, 5.441), stdev = 0.102
  CI (99.9%): [3.482, 7.217] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.686 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 5.411 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.000 ±(99.9%) 0.011 ms/op
Iteration   1: 4.699 ±(99.9%) 0.014 ms/op
Iteration   2: 4.887 ±(99.9%) 0.012 ms/op
Iteration   3: 4.857 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.814 ±(99.9%) 1.848 ms/op [Average]
  (min, avg, max) = (4.699, 4.814, 4.887), stdev = 0.101
  CI (99.9%): [2.967, 6.662] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 18.921 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.368 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.159 ±(99.9%) 0.006 ms/op
Iteration   1: 5.194 ±(99.9%) 0.014 ms/op
Iteration   2: 5.144 ±(99.9%) 0.007 ms/op
Iteration   3: 5.237 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.192 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (5.144, 5.192, 5.237), stdev = 0.046
  CI (99.9%): [4.344, 6.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.903 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 7.451 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.185 ±(99.9%) 0.015 ms/op
Iteration   1: 5.978 ±(99.9%) 0.016 ms/op
Iteration   2: 5.676 ±(99.9%) 0.017 ms/op
Iteration   3: 5.633 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.762 ±(99.9%) 3.422 ms/op [Average]
  (min, avg, max) = (5.633, 5.762, 5.978), stdev = 0.188
  CI (99.9%): [2.340, 9.185] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.858 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 6.589 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.616 ±(99.9%) 0.026 ms/op
Iteration   1: 5.359 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.269 ms/op
                 createUser·p0.50:   4.997 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   8.102 ms/op
                 createUser·p0.99:   10.682 ms/op
                 createUser·p0.999:  19.769 ms/op
                 createUser·p0.9999: 24.085 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   2: 5.282 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.208 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.627 ms/op
                 createUser·p0.95:   7.684 ms/op
                 createUser·p0.99:   10.977 ms/op
                 createUser·p0.999:  22.789 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 5.256 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.232 ms/op
                 createUser·p0.50:   4.891 ms/op
                 createUser·p0.90:   6.627 ms/op
                 createUser·p0.95:   7.602 ms/op
                 createUser·p0.99:   10.404 ms/op
                 createUser·p0.999:  22.449 ms/op
                 createUser·p0.9999: 26.441 ms/op
                 createUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181165
  mean =      5.299 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 96213 
    [ 5.000,  7.500) = 74102 
    [ 7.500, 10.000) = 8156 
    [10.000, 12.500) = 1896 
    [12.500, 15.000) = 329 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      2.208 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.782 ms/op
     p(99.0000) =     10.732 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     25.719 ms/op
     p(99.9990) =     27.643 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.772 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 5.766 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.157 ±(99.9%) 0.018 ms/op
Iteration   1: 4.810 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.499 ms/op
                 existUser·p0.50:   4.579 ms/op
                 existUser·p0.90:   5.816 ms/op
                 existUser·p0.95:   6.627 ms/op
                 existUser·p0.99:   9.224 ms/op
                 existUser·p0.999:  13.039 ms/op
                 existUser·p0.9999: 27.723 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   2: 5.109 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.318 ms/op
                 existUser·p0.50:   4.817 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   7.266 ms/op
                 existUser·p0.99:   9.208 ms/op
                 existUser·p0.999:  18.410 ms/op
                 existUser·p0.9999: 24.156 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   3: 5.008 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.273 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   6.201 ms/op
                 existUser·p0.95:   7.209 ms/op
                 existUser·p0.99:   9.765 ms/op
                 existUser·p0.999:  23.598 ms/op
                 existUser·p0.9999: 27.250 ms/op
                 existUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193128
  mean =      4.973 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 130848 
    [ 5.000,  7.500) = 55134 
    [ 7.500, 10.000) = 5699 
    [10.000, 12.500) = 945 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 79 

  Percentiles, ms/op:
      p(0.0000) =      2.273 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      6.119 ms/op
     p(95.0000) =      7.037 ms/op
     p(99.0000) =      9.388 ms/op
     p(99.9000) =     18.182 ms/op
     p(99.9900) =     27.066 ms/op
     p(99.9990) =     28.344 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.868 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 6.903 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.483 ±(99.9%) 0.020 ms/op
Iteration   1: 5.302 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   4.915 ms/op
                 getUser·p0.90:   6.595 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   11.076 ms/op
                 getUser·p0.999:  19.880 ms/op
                 getUser·p0.9999: 23.650 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 5.100 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.228 ms/op
                 getUser·p0.50:   4.825 ms/op
                 getUser·p0.90:   6.111 ms/op
                 getUser·p0.95:   7.146 ms/op
                 getUser·p0.99:   9.585 ms/op
                 getUser·p0.999:  22.246 ms/op
                 getUser·p0.9999: 28.860 ms/op
                 getUser·p1.00:   29.491 ms/op

Iteration   3: 5.086 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.490 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   5.939 ms/op
                 getUser·p0.95:   6.652 ms/op
                 getUser·p0.99:   8.847 ms/op
                 getUser·p0.999:  23.701 ms/op
                 getUser·p0.9999: 29.114 ms/op
                 getUser·p1.00:   30.048 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 185926
  mean =      5.161 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 109689 
    [ 5.000,  7.500) = 67645 
    [ 7.500, 10.000) = 6623 
    [10.000, 12.500) = 1282 
    [12.500, 15.000) = 362 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      6.185 ms/op
     p(95.0000) =      7.291 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     20.419 ms/op
     p(99.9900) =     28.522 ms/op
     p(99.9990) =     29.992 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.818 ±(99.9%) 0.297 ms/op
# Warmup Iteration   2: 7.775 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.097 ±(99.9%) 0.022 ms/op
Iteration   1: 6.033 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.671 ms/op
                 listUser·p0.50:   5.628 ms/op
                 listUser·p0.90:   7.397 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   11.551 ms/op
                 listUser·p0.999:  25.297 ms/op
                 listUser·p0.9999: 28.098 ms/op
                 listUser·p1.00:   28.869 ms/op

Iteration   2: 6.102 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.364 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  26.921 ms/op
                 listUser·p0.9999: 31.769 ms/op
                 listUser·p1.00:   32.866 ms/op

Iteration   3: 5.937 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.515 ms/op
                 listUser·p0.50:   5.571 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   11.370 ms/op
                 listUser·p0.999:  21.475 ms/op
                 listUser·p0.9999: 24.105 ms/op
                 listUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 159262
  mean =      6.023 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 16265 
    [ 5.000,  7.500) = 129019 
    [ 7.500, 10.000) = 10480 
    [10.000, 12.500) = 2473 
    [12.500, 15.000) = 448 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      5.661 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     25.133 ms/op
     p(99.9900) =     30.704 ms/op
     p(99.9990) =     32.400 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.828 ± 5.033  ops/ms
ClientPb.existUser                       thrpt       3   6.693 ± 2.568  ops/ms
ClientPb.getUser                         thrpt       3   6.233 ± 2.638  ops/ms
ClientPb.listUser                        thrpt       3   5.416 ± 4.012  ops/ms
ClientPb.createUser                       avgt       3   5.349 ± 1.868   ms/op
ClientPb.existUser                        avgt       3   4.814 ± 1.848   ms/op
ClientPb.getUser                          avgt       3   5.192 ± 0.848   ms/op
ClientPb.listUser                         avgt       3   5.762 ± 3.422   ms/op
ClientPb.createUser                     sample  181165   5.299 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.208           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.940           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.782           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.732           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.037           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.719           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.574           ms/op
ClientPb.existUser                      sample  193128   4.973 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.273           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.119           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.037           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.388           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.182           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.066           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  185926   5.161 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.175           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.866           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.291           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.142           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.419           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.522           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.048           ms/op
ClientPb.listUser                       sample  159262   6.023 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.747           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.438           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.600           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.133           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.704           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.866           ms/op
