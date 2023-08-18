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
# Warmup Iteration   1: 1.550 ops/ms
# Warmup Iteration   2: 3.513 ops/ms
# Warmup Iteration   3: 7.052 ops/ms
Iteration   1: 7.304 ops/ms
Iteration   2: 7.970 ops/ms
Iteration   3: 8.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.765 ±(99.9%) 7.296 ops/ms [Average]
  (min, avg, max) = (7.304, 7.765, 8.021), stdev = 0.400
  CI (99.9%): [0.469, 15.061] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.296 ops/ms
# Warmup Iteration   2: 7.189 ops/ms
# Warmup Iteration   3: 8.209 ops/ms
Iteration   1: 8.314 ops/ms
Iteration   2: 8.422 ops/ms
Iteration   3: 8.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.338 ±(99.9%) 1.359 ops/ms [Average]
  (min, avg, max) = (8.279, 8.338, 8.422), stdev = 0.074
  CI (99.9%): [6.980, 9.697] (assumes normal distribution)


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
# Warmup Iteration   1: 2.298 ops/ms
# Warmup Iteration   2: 6.384 ops/ms
# Warmup Iteration   3: 7.785 ops/ms
Iteration   1: 7.939 ops/ms
Iteration   2: 7.895 ops/ms
Iteration   3: 8.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.001 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (7.895, 8.001, 8.169), stdev = 0.147
  CI (99.9%): [5.313, 10.689] (assumes normal distribution)


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
# Warmup Iteration   1: 2.128 ops/ms
# Warmup Iteration   2: 5.513 ops/ms
# Warmup Iteration   3: 6.652 ops/ms
Iteration   1: 6.699 ops/ms
Iteration   2: 6.702 ops/ms
Iteration   3: 6.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.679 ±(99.9%) 0.687 ops/ms [Average]
  (min, avg, max) = (6.635, 6.679, 6.702), stdev = 0.038
  CI (99.9%): [5.992, 7.366] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 13.064 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.400 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.305 ±(99.9%) 0.007 ms/op
Iteration   1: 4.027 ±(99.9%) 0.006 ms/op
Iteration   2: 4.014 ±(99.9%) 0.008 ms/op
Iteration   3: 3.938 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.993 ±(99.9%) 0.876 ms/op [Average]
  (min, avg, max) = (3.938, 3.993, 4.027), stdev = 0.048
  CI (99.9%): [3.117, 4.869] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.726 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.004 ms/op
Iteration   1: 3.856 ±(99.9%) 0.006 ms/op
Iteration   2: 3.960 ±(99.9%) 0.007 ms/op
Iteration   3: 3.902 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.906 ±(99.9%) 0.952 ms/op [Average]
  (min, avg, max) = (3.856, 3.906, 3.960), stdev = 0.052
  CI (99.9%): [2.953, 4.858] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.053 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.660 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.007 ms/op
Iteration   1: 4.051 ±(99.9%) 0.005 ms/op
Iteration   2: 4.161 ±(99.9%) 0.005 ms/op
Iteration   3: 4.016 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.076 ±(99.9%) 1.383 ms/op [Average]
  (min, avg, max) = (4.016, 4.076, 4.161), stdev = 0.076
  CI (99.9%): [2.693, 5.459] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.263 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.679 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.755 ±(99.9%) 0.007 ms/op
Iteration   1: 4.779 ±(99.9%) 0.008 ms/op
Iteration   2: 4.659 ±(99.9%) 0.016 ms/op
Iteration   3: 4.728 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.722 ±(99.9%) 1.099 ms/op [Average]
  (min, avg, max) = (4.659, 4.722, 4.779), stdev = 0.060
  CI (99.9%): [3.624, 5.821] (assumes normal distribution)


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
# Warmup Iteration   1: 11.592 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.962 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.392 ±(99.9%) 0.018 ms/op
Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.089 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.243 ms/op
                 createUser·p0.99:   7.709 ms/op
                 createUser·p0.999:  12.292 ms/op
                 createUser·p0.9999: 25.043 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   2: 3.996 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.146 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   7.304 ms/op
                 createUser·p0.999:  25.985 ms/op
                 createUser·p0.9999: 27.984 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   3: 4.212 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.956 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   8.126 ms/op
                 createUser·p0.999:  24.775 ms/op
                 createUser·p0.9999: 37.019 ms/op
                 createUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234683
  mean =      4.088 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 366 
    [ 2.500,  5.000) = 217417 
    [ 5.000,  7.500) = 13805 
    [ 7.500, 10.000) = 2188 
    [10.000, 12.500) = 503 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     23.317 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     39.125 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


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
# Warmup Iteration   1: 12.613 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.062 ±(99.9%) 0.014 ms/op
Iteration   1: 3.865 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.396 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  13.451 ms/op
                 existUser·p0.9999: 24.746 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   2: 3.950 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   5.652 ms/op
                 existUser·p0.99:   8.225 ms/op
                 existUser·p0.999:  24.675 ms/op
                 existUser·p0.9999: 31.120 ms/op
                 existUser·p1.00:   31.916 ms/op

Iteration   3: 3.903 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.874 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   7.201 ms/op
                 existUser·p0.999:  14.756 ms/op
                 existUser·p0.9999: 33.384 ms/op
                 existUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245628
  mean =      3.906 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 235 
    [ 2.500,  5.000) = 233422 
    [ 5.000,  7.500) = 8971 
    [ 7.500, 10.000) = 2055 
    [10.000, 12.500) = 581 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     16.709 ms/op
     p(99.9900) =     32.371 ms/op
     p(99.9990) =     34.347 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 14.078 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 4.722 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.016 ms/op
Iteration   1: 4.057 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.708 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.920 ms/op
                 getUser·p0.999:  22.413 ms/op
                 getUser·p0.9999: 28.815 ms/op
                 getUser·p1.00:   30.376 ms/op

Iteration   2: 4.024 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.343 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   5.111 ms/op
                 getUser·p0.99:   7.602 ms/op
                 getUser·p0.999:  25.919 ms/op
                 getUser·p0.9999: 29.198 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   3: 4.028 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.474 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   7.725 ms/op
                 getUser·p0.999:  12.244 ms/op
                 getUser·p0.9999: 31.593 ms/op
                 getUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 237699
  mean =      4.036 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 225235 
    [ 5.000,  7.500) = 9783 
    [ 7.500, 10.000) = 1705 
    [10.000, 12.500) = 630 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     22.413 ms/op
     p(99.9900) =     30.399 ms/op
     p(99.9990) =     32.338 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 14.386 ±(99.9%) 0.226 ms/op
# Warmup Iteration   2: 5.613 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.169 ±(99.9%) 0.020 ms/op
Iteration   1: 4.868 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.504 ms/op
                 listUser·p0.99:   9.912 ms/op
                 listUser·p0.999:  24.773 ms/op
                 listUser·p0.9999: 27.914 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   2: 4.924 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.530 ms/op
                 listUser·p0.95:   6.472 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  20.087 ms/op
                 listUser·p0.9999: 25.297 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   3: 5.075 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.095 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   5.603 ms/op
                 listUser·p0.95:   7.176 ms/op
                 listUser·p0.99:   10.240 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 20.418 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 193644
  mean =      4.954 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 136625 
    [ 5.000,  7.500) = 49246 
    [ 7.500, 10.000) = 5832 
    [10.000, 12.500) = 1125 
    [12.500, 15.000) = 273 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.884 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      6.767 ms/op
     p(99.0000) =      9.994 ms/op
     p(99.9000) =     20.426 ms/op
     p(99.9900) =     26.780 ms/op
     p(99.9990) =     28.514 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.765 ± 7.296  ops/ms
ClientPb.existUser                       thrpt       3   8.338 ± 1.359  ops/ms
ClientPb.getUser                         thrpt       3   8.001 ± 2.688  ops/ms
ClientPb.listUser                        thrpt       3   6.679 ± 0.687  ops/ms
ClientPb.createUser                       avgt       3   3.993 ± 0.876   ms/op
ClientPb.existUser                        avgt       3   3.906 ± 0.952   ms/op
ClientPb.getUser                          avgt       3   4.076 ± 1.383   ms/op
ClientPb.listUser                         avgt       3   4.722 ± 1.099   ms/op
ClientPb.createUser                     sample  234683   4.088 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.149           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.971           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.317           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.603           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.191           ms/op
ClientPb.existUser                      sample  245628   3.906 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.497           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.973           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.807           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.709           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.371           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.669           ms/op
ClientPb.getUser                        sample  237699   4.036 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.708           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.046           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.700           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.413           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.399           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.834           ms/op
ClientPb.listUser                       sample  193644   4.954 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.884           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.767           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.994           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.426           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.780           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.606           ms/op
